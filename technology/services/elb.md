# Elastic Load Balance (ELB)

O Elastic Load Balancing (ELB) distribui automaticamente o tráfego de entrada de aplicativos **em vários destinos**, **como instânciasdo Amazon EC2, contêineres e endereços IP**. Ele pode lidar com a carga variável do tráfego do seu aplicativo em **uma única zona de disponibilidade ou em várias zonas de disponibilidade**. O Elastic Load Balancing oferece **três tipos** de load balancers, todos com alta disponibilidade, dimensionamento automático e segurança robusta necessária para tornar seus aplicativos tolerantes a falhas.

* **O Application Load Balancer** é mais adequado para balanceamento de carga de tráfego **HTTP e HTTPS**
* **O Network Load Balancer** é mais adequado para balanceamento de carga de **tráfego TCP**, onde é necessário desempenho extremo.
* O Classic Load Balancer opera no nível de solicitação e no nível de conexão. O Classic Load Balancer destina-se a aplicativos criados na **rede EC2-Classic**.

Para saber mais sobre este serviço acesse: 
    
  * [Elastic Load Balance](https://docs.aws.amazon.com/elasticloadbalancing/?icmpid=docs_homepage_networking)