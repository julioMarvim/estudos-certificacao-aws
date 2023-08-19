# Modelo de Responsabilidade Compatilhada

**Segurança e conformidade são responsabilidades compartilhadas entre a AWS e o cliente**. Esse modelo compartilhado pode ajudar a aliviar a carga operacional do cliente, pois a AWS opera, gerencia e controla os componentes do sistema operacional do host e da camada de virtualização até a segurança física das instalações nas quais o serviço opera. **O cliente assume a responsabilidade e o gerenciamento do sistema operacional convidado (incluindo atualizações e patches de segurança), outro software de aplicativo associado, bem como a configuração do firewall do grupo de segurança fornecido pela AWS.**

Os clientes devem considerar cuidadosamente os serviços que escolhem, **pois suas responsabilidades variam de acordo com os serviços usados, a integração desses serviços em seu ambiente de TI e as leis e regulamentos aplicáveis**. A natureza dessa responsabilidade compartilhada também fornece a flexibilidade e o controle do cliente que permitem a implantação. A diferenciação de responsabilidade é comumente referida como **Segurança “da” Nuvem** versus **Segurança “na” Nuvem**.

### Responsabilidade da AWS “Segurança da Nuvem”

A AWS é **responsável** por proteger a **infraestrutura que executa todos os serviços oferecidos na Nuvem AWS**. Essa infraestrutura é composta por **hardware, software, rede e instalações** que executam os serviços da Nuvem AWS.

### Responsabilidade do cliente “Segurança na Nuvem”

**A responsabilidade do cliente será determinada pelos serviços de Nuvem AWS selecionados pelo cliente**. Isso determina a quantidade de trabalho de **configuração** que o cliente deve realizar **como parte de suas responsabilidades de segurança**.

Um serviço como o Amazon Elastic Compute Cloud (Amazon EC2) é classificado como Infraestrutura como Serviço (IaaS) e, como tal, exige que o **cliente execute todas as tarefas de configuração e gerenciamento de segurança necessárias**. Os clientes que implantam uma instância do Amazon EC2 são **responsáveis pelo gerenciamento do sistema operacional convidado (incluindo atualizações e patches de segurança), qualquer software de aplicativo ou utilitários instalados pelo cliente nas instâncias e pela configuração do firewall fornecido pela AWS (chamado de segurança grupo) em cada instância**.

Para serviços abstratos, **como Amazon S3 e Amazon DynamoDB**, a AWS opera a camada de infraestrutura, o sistema operacional e as plataformas, e os clientes acessam os endpoints para armazenar e recuperar dados. **Os clientes são responsáveis por gerenciar seus dados (incluindo opções de criptografia), classificar seus ativos e usar ferramentas IAM para aplicar as permissões apropriadas**.

## Representação do modelo de responsabilidade compatilhada

![Modelo de responsabilidade compartilhada](/images/shared-responsability-model.png)

Para saber mais sobre este assunto acesse: 
    
  * [Shared responsability model](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/bestpracticesguide/security-shared.html)