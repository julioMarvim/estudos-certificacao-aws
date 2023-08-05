# Metodos de Deployng e Operações na nuvem AWS

Basicamente iremos discutir como é feito o deploy e como fazer essa operação na nuvem AWS. 
É importante salientar que para esta certificação ACP não precisaremos nos aprofundar nesses serviços, apenas conhece-los superficialmente.

## AWS Elastic Beanstalk

É um serviço de **deployng** e **scaling** para alicações WEB e serviços desenvolvidos com
**Java, .NET, PHP, Node.js, Python, Ruby, Go e Docker** nos servidores mais comuns como
**Apache, Nginx, Passanger e IIS**.

Voce pode simplesmente fazer o upload do código e o **Elastic Beanstalk automaticamente realiza o deploy provisionando capacidade, load balancing, auto-scaling e monitoramento de vida da aplicação**.

Basicamente, o usuário precisa se preocupar apenas em fazer o upload do código, o Elastc Beanstalk irá provisionar toda a infraestrutura pra vocé. 

  ### Importante
        Este serviço por si só não é cobrado, o que é cobrado será a infraestrutura que ele irá provisionar para você.

  Para saber mais sobre este serviço acesse: 
    
  * [AWS Elastic Beanstalk](https://aws.amazon.com/pt/elasticbeanstalk/)