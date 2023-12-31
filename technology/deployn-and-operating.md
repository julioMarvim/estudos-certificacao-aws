# Metodos de Deployng e Operações na nuvem AWS

Basicamente iremos discutir como é feito o deploy e como fazer essa operação na nuvem AWS. 
É importante salientar que para esta certificação ACP não precisaremos nos aprofundar nesses serviços, apenas conhece-los superficialmente.

Os serviços que iremos falar nesse momento são: 

* AWS Elastic Beanstalk
* AWS CloudFromation
* AWS OpsWorks
* AWS CodeCommit
* AWS CodeDeploy
* AWS CodePipeline
* AWS EC2 Container Service

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


## AWS CloudFormation

O AWS CloudFormation prove uma **linguágem** com **templates** nos quais o usuário pode providenciar **qualquer serviço da AWS**. Diferentemente do Beanstalk que era usado apenas para aplicações web.

Basicamente vc cria este template com umn arquivo de texto simples e adiciona este arquivo no CloudFormation e ele provisiona a infraestrutura pra você. Podemos ainda criar nossos proprios templates, usar templates prontos e salvar estes templates em um bucket S3 para reutilizar em outros momentos.  


 Para saber mais sobre este serviço acesse: 
    
  * [AWS CloudFormation](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/Welcome.html)


  ## AWS OpsWorks

  O AWS OpsWorks é um gestor de provisonamento de configurações, ele providencia e gerencia instâncias de **Chef** e **Puppet**. Estas são plataformas de automação que permitem que o usuário use codigos para automatizar as configurações dos seus serviços. OpsWorks pode usar Chef e Puppet para automatizar como servidores são **configurados, como os deploy são realizados e gerenciados** atravez das instancias EC2 ou variaveis de computaçao on-premies.

   Para saber mais sobre este serviço acesse: 
    
  * [AWS OpsWorks](https://docs.aws.amazon.com/opsworks/latest/userguide/welcome.html)


  ## AWS CodeCommit

  AWS CodeCommit é um **source controll service** que permite armazenar repositorios privados do Git. Ele facilita a gestão e colaboração de times de forma **totalmente segura e escalável**. O usuário não precisa se preocupar com escalabilidade e infraestrutura para este fim. E ele é totalmente compativel com as ferramentas Git existentes.

 Para saber mais sobre este serviço acesse: 
    
  * [AWS CodeCommit](https://www.amazonaws.cn/en/codecommit/)


  ## AWS CodeDeploy

  É um serviço de **Implantação** totalmente gerenciado e **automático**, ele automatiza implantações de software em vários serviços **EC2**, **AWS Fargate**, **EC2**, **AWS Lambda** e até mesmo **on-premises**. Ele é usado para automatizar a implantação e eliminar qualquer ação manual neste processo. 

 Para saber mais sobre este serviço acesse: 
    
  * [AWS CodeDeploy](https://aws.amazon.com/pt/codedeploy/)


## AWS CodePipeline

É um serviço totalmente gerenciavel de entrega contínua **(delivery service)**, que ajuda você a automatizar a automatizar suas pipelines de deploy. Este serviço automatiza os processos de **Build, test, deploy, scaling, entre outros**. 

### Importante

    Você não tem um investimento inicial ou seja **upfront fees**(CAPEX), que é o dinheiro que vc teria que fazer para provisionar a aplicação. 

 Para saber mais sobre este serviço acesse: 
    
  * [AWS CodePipeline](https://aws.amazon.com/pt/codepipeline/)


## AWS EC2 Container Services

O Amazon ECS permite que você facilmente **rode, escale e dimensione** aplicações Docker na AWS. Ele elimina a necessidade de instalar, operar e escalar seu proprio **container cochestraiton** e infraestrutura de **cluster managements**.

Dentro do ECS nos temos o AWS Fargate que nos permite gerenciar a infraestrutura dentro do cluster.

 Para saber mais sobre este serviço acesse: 
    
  * [AWS EC2 Container Services](https://aws.amazon.com/pt/ecs/)