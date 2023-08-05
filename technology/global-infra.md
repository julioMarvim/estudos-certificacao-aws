## Infraestrutura Global da AWS

A infraestrutura global da AWS está distibuida em **Regões (Regions)** **Zonas de Disponibilidade (Availability Zones)**, onde as zonas de disponibilidade estão contidas dentro das regiões. As Regions possuem muitiplos Availability Zones e as Availability Zones
consistem em **um ou mais Data Centers.**

Cada Availability Zones possui a sua própria estrutura de redundância ou seja, elas são isoladas entre sí, possuem **alta disponibilidade, capacidade e são tolerantes a falhas**.
Esta estrutura traz a vantagem de redundância se comparada a um data center comum. 

Veja a seguir a infraestrutura global da AWS:
* [Saiba mais sobre a infraestrutura global da AWS](https://aws.amazon.com/pt/about-aws/global-infrastructure/?hp=tile&tile=map)


### Regiões

É importante guardar que cada região da AWS é completamente isolada uma da outra, isso acontece para garantir que a infra da AWS seja <strong>mais segura, com maior capacidade e tolerância a falhas</strong>

## Zonas de Disponibilidade

As Zonas de Disponibilidade são isoladas, no que diz respeito a infraestrutura física, mas as zonas de uma mesma de uma região são interconectadas com **links de baixa latencia**. Como elas são projetadas para serem tolerântes a falhas, na falta de uma a outra funciona plenamente.

**O MINIMO DE ZONA DE DISPONIBILIDADE POR REGIÃO SÃO 2.** 

## Edge Locations

Outro ponto importante na infraestrurura da AWS são os **Edge Locations**, que são os endpoints que a AWS usa para fazer **caching de conteúdos**, para facilitar o acesso aos dados com baixa latencia. Estas estruturas de Edge Locations são tipicamente usadas pelo 
serviço de CloudFront que é o CDN da AWS. 

### Resumindo a quantidade itens da Infra AWS

Termos mais Edge Locations que Availability Zones e Mais Availability Zones que Regions.

**Edge Locations > Availability Zones > Regions**
