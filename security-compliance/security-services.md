# Serviços - Segurança, Identidade e Conformidade

* WAF , Shield 
* Inspector, Trusted Advisor, CloudTrail
* Cloudwatch, AWS Config
* Athena, Macie


## AWS WAF 
AWS WAF é um firewall de aplicativo web que ajuda a **proteger seus aplicativos web ou APIs contra explorações comuns da web** que podem afetar a disponibilidade, comprometer a segurança ou consumir recursos excessivos. O AWS WAF oferece controle sobre como o tráfego chega a seus aplicativos, permitindo que você crie **regras de segurança** que bloqueiam padrões de ataque comuns, como **SQL injection** ou **cross-site scripting**, e regras que filtram padrões de tráfego específicos **definidos por você**.

AWS WAF, **você paga apenas pelo que usar**. O preço é baseado em quantas regras você implanta e quantas solicitações da web seu aplicativo recebe. Não há compromissos iniciais.

Você pode implantar o AWS WAF no Amazon **CloudFront** como parte de sua solução CDN, o **Application Load Balancer** que faz frente a seus servidores web ou servidores de origem em execução no EC2 ou Amazon API Gateway para suas APIs.

Para saber mais sobre este serviço acesse: 
    
  * [AWS WAF](https://docs.aws.amazon.com/waf/index.html)


## AWS Shield - DDoS Protection 

O AWS Shield é um serviço gerenciado de **proteção contra Denial of Service (DDoS)** que protege os aplicativos executados na AWS. O AWS Shield fornece detecção sempre ativa e mitigações automáticas em linha que **minimizam** o tempo de **inatividade** e a **latência** do aplicativo, portanto, não há necessidade de envolver o AWS Support para se beneficiar da proteção contra DDoS. Existem dois níveis de AWS Shield - **Standard** e **Advanced**.

### AWS Shield Standard

O AWS Shield Standard **fornece monitoramento de fluxo de rede sempre ativo, que inspeciona o tráfego de entrada para a AWS** e usa uma **combinação de assinaturas de tráfego**, algoritmos de anomalia e outras técnicas de análise para **detectar tráfego malicioso em tempo real.**

### AWS Shield Advanced

Você também pode mitigar ataques DDoS na camada de aplicativo **escrevendo regras** usando o AWS WAF. Com o **AWS WAF você paga apenas pelo que usa**. Basicamente a diferença é que no Advanced vc pode **customizar suas regras**. 

## Standard x Advanced
Standard                                                | Advanced
----------------------------------                      | -------------
Disponível automaticamente em todos os serviços da AWS. | Amazon Route 53
X                                                       | Amazon CloudFront
X                                                       | Elastic Load Balancing
X                                                       | AWS Global Accelerator
X                                                       | Elastic IP (Amazon Elastic Compute Cloud and Network Load Balancer)

Para saber mais sobre este serviço acesse: 
    
  * [AWS Shield](https://docs.aws.amazon.com/pt_br/waf/latest/developerguide/shield-chapter.html)


## Amazon Inspector

O Amazon Inspector é um serviço **automatizado de avaliação de segurança que ajuda a melhorar a segurança e a conformidade dos aplicativos implantados na AWS**. O Amazon Inspector avalia automaticamente os aplicativos quanto **à exposição, vulnerabilidades e desvios das práticas recomendadas**. Depois de realizar uma avaliação, o Amazon Inspector produz uma lista detalhada de descobertas de segurança priorizadas por nível de gravidade. Essas descobertas podem ser revisadas diretamente ou como parte de relatórios de avaliação detalhados que estão disponíveis por meio do console ou API do Amazon Inspector.

As avaliações de segurança do Amazon Inspector ajudam você a verificar a acessibilidade de rede não intencional de suas instâncias do **Amazon EC2** e as vulnerabilidades nessas instâncias do EC2.

Para saber mais sobre este serviço acesse: 
    
  * [AWS Inspector](https://docs.aws.amazon.com/inspector)


## AWS Trusted Advisor

O AWS Trusted Advisor é uma **ferramenta online** que fornece orientação em tempo real para ajudá-lo a provisionar seus recursos seguindo as melhores práticas da AWS.

Seja estabelecendo novos fluxos de trabalho, desenvolvendo aplicativos ou como parte de uma melhoria contínua, aproveite as recomendações fornecidas pelo Trusted Advisor regularmente para ajudar a manter suas soluções provisionadas de maneira ideal.

Para saber mais sobre este serviço acesse: 
    
  * [AWS Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)


## AWS CloudTrail

AWS CloudTrail é um serviço que permite **governança, conformidade, auditoria operacional e auditoria de risco de sua conta AWS**. Com o CloudTrail, **você pode registrar, monitorar continuamente e reter a atividade da conta relacionada a ações em sua infraestrutura da AWS**. O CloudTrail **fornece histórico de eventos da atividade da sua conta da AWS**, incluindo ações realizadas por meio do AWS Management Console, AWS SDKs, ferramentas de linha de comando e outros serviços da AWS. Esse histórico de eventos simplifica a análise de segurança, o rastreamento de alterações de recursos e a solução de problemas. Além disso, você pode usar o **CloudTrail para detectar atividades incomuns em suas contas**.

Para saber mais sobre este serviço acesse: 
    
  * [AWS CloudTrail](https://docs.aws.amazon.com/cloudtrail/)


## AWS CloudWatch

O Amazon CloudWatch fornece dados e insights acionáveis para monitorar seus aplicativos, responder a alterações de desempenho em todo o sistema, otimizar a utilização de recursos e obter uma visão unificada da integridade operacional. **O CloudWatch coleta dados operacionais e de monitoramento na forma de logs, métricas e eventos, fornecendo a você uma visão unificada dos recursos, aplicativos e serviços da AWS executados na AWS e em servidores locais**. Você pode usar o CloudWatch para detectar anomalias, definir alarmes, visualizar logs e métricas lado a lado, tomar ações automatizadas e solucionar problemas.

  Para saber mais sobre este serviço acesse: 
    
  * [AWS CloudWatch](https://docs.aws.amazon.com/cloudwatch/)


## AWS Config

AWS Config é um serviço que permite **avaliar, auditar e avaliar** as configurações dos seus recursos da AWS. O Config monitora e registra continuamente suas configurações de recursos da AWS e permite que você automatize a avaliação das configurações registradas em relação às configurações desejadas. Com o Config, você pode **revisar alterações nas configurações e relacionamentos entre recursos da AWS**, mergulhar em históricos detalhados de configuração de recursos e determinar sua conformidade geral em relação às configurações especificadas em suas diretrizes internas.

   Para saber mais sobre este serviço acesse: 
    
  * [AWS Config](https://docs.aws.amazon.com/config/)


## AWS Athena  

O Amazon Athena é um serviço de **consulta interativa** que **facilita a análise de dados no Amazon S3 usando SQL padrão**. O Athena não tem servidor, portanto, não há infraestrutura para gerenciar e **você paga apenas pelas consultas executadas**.

Basta apontar para seus dados no Amazon S3, definir o esquema e começar a consultar usando o SQL padrão. Com o Athena, não há necessidade de tarefas ETL complexas para preparar seus dados para análise. Isso torna mais fácil para qualquer pessoa com habilidades em SQL analisar rapidamente conjuntos de dados em grande escala.

Para saber mais sobre este serviço acesse: 
    
  * [AWS Athena](https://docs.aws.amazon.com/athena/)


## AWS Macie

O Amazon Macie é um serviço de segurança que usa **aprendizado de máquina** para **descobrir, classificar e proteger automaticamente dados confidenciais na AWS**. O Amazon Macie reconhece dados confidenciais, como **informações de identificação pessoal (PII)** ou propriedade intelectual, e fornece painéis e alertas que dão visibilidade sobre como esses dados estão sendo acessados ou movidos. O serviço totalmente gerenciado monitora continuamente a atividade de acesso a dados em busca de anomalias e gera alertas detalhados quando detecta risco de acesso não autorizado ou vazamento inadvertido de dados.

Hoje, o Amazon Macie está **disponível** para **proteger os dados armazenados no Amazon S3**, com suporte para armazenamentos de dados adicionais da AWS no final deste ano.

Para saber mais sobre este serviço acesse: 
    
  * [AWS Macie](https://docs.aws.amazon.com/macie/)