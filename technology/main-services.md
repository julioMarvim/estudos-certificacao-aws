# Principais Serviços da AWS

* IAM - Identity and Access Management
* S3 - Amazon Simple Storage Service
* EC2 - Elastic Compute Cloud

### IAM - Identity and Access Management

O AWS IAM nos permite **controlar e habilidar** de forma segura os acessos aos **serviços e recurosos** da AWS para o nosso **usuários**. Usando o IAM nós podemos criar e gerenciar **usuarios e grupos**, fronecendo ou removendo permissões para os mesmos. 

* Gerenciar os usuarios IAM e seus acessos.
* Gerenciar as roles IAM e suas permissões.
* Gerenciar usuários federados e suas permissões.

Para saber mais sobre este serviço acesse: 
    
  * [IAM - Identity and Access Management](https://docs.aws.amazon.com/pt_br/whitepapers/latest/navigating-gdpr-compliance/aws-identity-and-access-management.html)

### S3 - Amazon Simple Storage Service

Amazon S3 é um **object storage** ou seja um serviço de armazenamento de objetos, que oferece escalabilidade, disponibilidade de dados e performace. 

Este serviço é projetado para possuir autissima disponibilidade, cerca de 99,**999999999%** e é usado por milhões de companias ao redor do mundo.

* Baseado em objetos(object-based)
* Tamanho dos arquivos - 0 a 5Tb
* Key (nome do objeto)
* Armazenamento ilimitado
* Armazenamento em Buckets

Para saber mais sobre este serviço acesse: 
    
  * [S3 - Amazon Simple Storage Service](https://docs.aws.amazon.com/s3/?icmpid=docs_homepage_featuredsvcs)

### EC2 - Elastic Compute Cloud

O Amazon ec2 é um serviço da web que fornece capacidade de computação segura e redimensionável na nuvem. Ele foi projetado para tornar a computação em escala da Web mais fácil para os desenvolvedores.

O Amazon EC2 reduz o tempo necessário para obter e inicializar uma nova instância do servidor (chamada instância do Amazon EC2) para minutos, permitindo que você dimensione rapidamente a capacidade, tanto para cima quanto para baixo, conforme sua computação requer alterações.

O Amazon EC2 muda a economia da computação permitindo  que você pague apenas pela capacidade que você realmente usa.

## Tipos de Instâncias EC2

### On-Demand instances

* Instâncias Sob Demanda (On-Demand) — Com instâncias On-Demand, **você paga pela capacidade de computação por hora**, sem **compromissos de longo prazo**. Você pode aumentar ou diminuir sua capacidade de computação dependendo das demandas de seu aplicativo e pagar apenas a taxa por hora especificada pelas instâncias que usar.

* O uso de instâncias On-Demand libera você dos **custos e complexidades de planejamento, compra e manutenção de hardware e transforma o que normalmente são grandes custos fixos em custos variáveis muito menores**. As instâncias On-Demand também eliminam a necessidade de comprar capacidade de **“rede de segurança”** para lidar com picos de tráfego periódicos.

### Reserved Instances

* As Instâncias reservadas (Reserved Instances) oferecem um desconto significativo **(até 75%) em comparação com o preço da instância On-Demand**. Você tem a flexibilidade de alterar famílias, tipos de sistema operacional e locações enquanto se beneficia da definição de preço de Instância reservada ao usar Instâncias reservadas conversíveis.


### Spot Instances

* As instâncias Spot estão disponíveis com um desconto de até **90% em comparação com os preços On-Demand** e permitem que você aproveite a capacidade não utilizada do EC2 na Nuvem AWS. Você pode reduzir significativamente o custo de execução de seus aplicativos, aumentar a capacidade de computação e o rendimento de seu aplicativo com o mesmo orçamento e habilitar novos tipos de aplicativos de computação em nuvem.

### Dedicated Hosts

* Um Amazon EC2 Dedicated Host é um **servidor físico com capacidade de instância EC2 totalmente dedicada ao seu uso**. Hosts dedicados podem ajudá-lo a atender aos requisitos de conformidade e reduzir custos, **permitindo que você use suas licenças de software vinculadas ao servidor existentes**.

Para saber mais sobre este serviço acesse: 
    
  * [EC2 - Elastic Compute Cloud](https://docs.aws.amazon.com/ec2/?icmpid=docs_homepage_featuredsvcs)