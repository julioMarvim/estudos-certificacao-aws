# Como escolher uma Região da AWS

Segundo a AWS para escolhermos uma região, devemos levar em consideração os seguintes pontos

## Lei de armazenamento de dados

Devemos considerar as leis de porteção a dados do país em que escolhemos a região, é importante estar alinhado a questões legais do país daquela região que formos escolher. Cada lugar tem suas regras.

## Latencia para os Usuários finais

Mesmo consideranto todas as questões da infraestrutura que melhoram a latencia, como edge locations e AZs, se nosso sitema estiver em uma região muito distante do nosso usuário final essa latencia certamente será muito alta. Por exemplo, nosso banco de dados está na Azia e u usuário final está na America do Norte. Por isso, hospede sua aplicação em regiões priximas ao seu usuário final. 

## Serviços da AWS

Os serviços da AWS são divididos em **serviços globais** e **serviços regionais**. Então 
é importante considerar estes pontos ao escolher uma região. Se noss aplicação for utilizar um serviço regional precisamos consultar em qual região este serviço está disponível.

### Como acessar os serviço da AWS

De tres maneiras distintas: 
1. AWS Management Console
  
    É a interface gráfica da AWS, é o lugar onde podemos acessar e gerenciar todos os serviços da AWS de forma visual e amigável.
  
    * [AWS Management Console](https://docs.aws.amazon.com/pt_br/awsconsolehelpdocs/latest/gsg/learn-whats-new.html)

2.  Comand Line Interface (CLI)

    E a ferarmenta utilizada para acessar os serviços da AWS via linha de comando, é um software que instalamos na nossa máquina. 

    * [AWS Command Line Interface](https://docs.aws.amazon.com/cli/index.html) 

3. Softare Development Kit (SDKs)

    São os vários SDKs disponíveis para possamos interagir com os serviços diretamente em nossas aplicações. 

    * [Tools to Build on AWS](https://aws.amazon.com/developer/tools/?nc1=h_ls)