# Modulo 2



As redes são constituidas de 3 componentes fundamentais

1 - nós (equipamentos, switch, roteadores, servidores)

2 - protocolos (regras que fazem a comunicação funcionar)

3 - enlace (conexão por meio físico, fibra, wireless, cobre etc)



Ponto a ponto e Ponto Multiponto



Basicamente o ponto a ponto é quando dois dispositivos estão conectados diretamente e tem um meio fisico dedicado a apenas esses dois equipamentos

No ponto multiponto, um equipamento tem conexões com outros devices ao mesmo tempo e as vezes compartilhando o meio fisico.



Ex ponto a ponto: 2 pessoas conversando sem ninguem por perto

ex ponto multiponto: uma pessoa dando palestra e varias outras ouvindo



A topologia de uma rede é representada na forma em que as ligações entres os seus componentes são feitas. Existem as topologias fisicas e lógicas



temos exemplos de topologias fisicas como:

barramento 

![](https://stecine.azureedge.net/repositorio/00212ti/00087/img/11.jpg)

estrela

![](https://stecine.azureedge.net/repositorio/00212ti/00087/img/12.jpg)

full mesh

![](https://stecine.azureedge.net/repositorio/00212ti/00087/img/15.jpg)

distribuidas / parcialmente conectadas

![](https://stecine.azureedge.net/repositorio/00212ti/00087/img/16.jpg)

anel

![](https://stecine.azureedge.net/repositorio/00212ti/00087/img/13.jpg)

arvore/hierarquica

![](https://stecine.azureedge.net/repositorio/00212ti/00087/img/14.jpg)



Topologias lógicas são as tecnicas de como os dados se comportam perante esse meio físico e não necessariamente se comportaram conforme o meio fisico. Por exemplo um Hub em que as conexão dos dispositivos de forma fisica é feito em estrela, porém de forma lógica se comporta como um barramento, propagando os dados para todos os devices conectados. Outro exemplo seria a topologia em Anel, switchs conectados em forma de anel, mas logicamente os dados não podem "correr" em anel se não teria loop



Classificação quanto a área de cobertura

Temos as redes PAN que são redes pessoais, ou seja dispositivos como celular, smartwatch, cartão NFC, e todas essas pequenas redes juntas para ser compartilhada elas foram uma LAN e quando está conectada em uma rede de algum provedor (acesso a internet) todas essas LANs forma uma MAN e dependendo do provedor, caso tenha varias MANs juntas, formam uma WAN e conectando com diversos outros provedores formam a internet propriamente dita



PAN - Personal Area Network

LAN - Local Area Network

MAN - Metropolitan Area Network

WAN - Wide Area Network

Internet - Inter-conexão de redes distintas de forma global



Meios de transmissão


Redes cabeadas e Redes Sem fio



Redes cabeadas: auto explicativo, utilizam cabos como meio de propagação dos dados, sendo guiado e temos examplos como

 o cabo de cobre (o famoso cabo UTP), que transportam sinal eletromagnetico mas sofrem interferencias

, cabo optico (fibra) que transporta sinal de luz e suportam altas velocidades de transmissão mas são bem mais caros

e o coaxial, mesma coisa do de cobre porém limitado e mais rigido



Redes sem fio: O sinal é transmitido em espaço aberto sem ser guiado. Temos tecnologias de redes sem fio que sao classificadas por conta da frequência



Rede por infravermelho (frequencia maior ainda) e quase não quebra barreiras e muito menos alcance

Rede por microondas (frequencia mais alta, gigahertz) ondas menores, mais direcionais, propagam em linha reta, e não quebram barreiras com muita facilidade e menos alcance

Rede por radio (frequencias baixas, na ordem de kilo e megahertz), ondas maiores, propaga em varias direções e quebram barreiras mais facilmente e maior alcance