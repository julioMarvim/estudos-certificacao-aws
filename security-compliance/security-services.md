# Serviços - Segurança, Identidade e Conformidade

* WAF , Shield 
* Inspector, Trusted Advisor, CloudTrail
* Cloudwatch, AWS Config
* Athena, Macie


## AWS WAF 
AWS WAF é um firewall de aplicativo web que ajuda a **proteger seus aplicativos web ou APIs contra explorações comuns da web** que podem afetar a disponibilidade, comprometer a segurança ou consumir recursos excessivos. O AWS WAF oferece controle sobre como o tráfego chega a seus aplicativos, permitindo que você crie **regras de segurança** que bloqueiam padrões de ataque comuns, como **SQL injection** ou **cross-site scripting**, e regras que filtram padrões de tráfego específicos **definidos por você**.

AWS WAF, **você paga apenas pelo que usar**. O preço é baseado em quantas regras você implanta e quantas solicitações da web seu aplicativo recebe. Não há compromissos iniciais.

Você pode implantar o AWS WAF no Amazon **CloudFront** como parte de sua solução CDN, o **Application Load Balancer** que faz frente a seus servidores web ou servidores de origem em execução no EC2 ou Amazon API Gateway para suas APIs.

Para saber mais sobre este assunto acesse: 
    
  * [AWS WAF](https://docs.aws.amazon.com/waf/index.html)


## AWS Shield - DDoS Protection 

O AWS Shield é um serviço gerenciado de **proteção contra Denial of Service (DDoS)** que protege os aplicativos executados na AWS. O AWS Shield fornece detecção sempre ativa e mitigações automáticas em linha que **minimizam** o tempo de **inatividade** e a **latência** do aplicativo, portanto, não há necessidade de envolver o AWS Support para se beneficiar da proteção contra DDoS. Existem dois níveis de AWS Shield - **Standard** e **Advanced**.

### AWS Shield Standard

O AWS Shield Standard **fornece monitoramento de fluxo de rede sempre ativo, que inspeciona o tráfego de entrada para a AWS** e usa uma **combinação de assinaturas de tráfego**, algoritmos de anomalia e outras técnicas de análise para **detectar tráfego malicioso em tempo real.**

### AWS Shield Advanced

Você também pode mitigar ataques DDoS na camada de aplicativo **escrevendo regras** usando o AWS WAF. Com o **AWS WAF você paga apenas pelo que usa**. Basicamente a diferença é que no Advanced vc pode **customizar suas regras**. 

Para saber mais sobre este assunto acesse: 
    
  * [AWS Shield](https://docs.aws.amazon.com/pt_br/waf/latest/developerguide/shield-chapter.html)


