# NEECMESH
Repo para o NEECMESH

Neste repo iremos guardar os ficheiros relativos ao NEECMESH, iremos ter a parte "teorica" e a pratica.
Na teorica cabe a investigação e objetivos ( e etc)
Na pratica cabe o design da esquematica (e eventual PCB), com o BOM ( bill of material, ou seja o material todo)
Também numa mistura entre pratico e teorico as fontes de material, era bom se desse para evitar MOUSER e DIGIKEY, mas não é facil, também é melhor usarmos componentes "genericos" ou pelo menos disponiveis na https://www.lcsc.com/ porque assim podiamos evitar o custo de comprar e de soldar.

É suposto fazerem clone do projeto do KiCAD e façam as partes referentes ao vosso modulo.
A esquematica podia ser separada em varias, mas não o iremos fazer.

Objetivos

- [ ] Fazer pesquisa de tudo...
  - [ ] MCU (seleção inicial com vantagens/desvantagens
    - [ ] Escolha final e porque
  - [ ] BMU
    - [ ] Escolha do IC de carregamento com o circuito de proteção
    - [ ] Escolha da "Bateria" Lipo OU LiOn (Ou seja cilindrica ou retangular lisa)
    - [ ] Carregamento sem fios?
  - [ ] RADIO
    - [ ] Ver a banda apropriada para comunicação dentro de uma casa
    - [ ] Escolher como implementar
    - [ ] Não sei mais pq não sou de TELE
  - [ ] SENSORES
    - [ ] Escolher o que vamos medir, temperatura, Humidade, presença
    - [ ] Como vamos medir, ou seja os ICs ou componentes necessarios
    - [ ] Se precissamos de montagens de suporte pre-MCU
    - [ ] Consumo de cada um e os seus polling times
