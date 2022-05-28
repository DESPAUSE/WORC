## ***High Concept***
# **WORC**

* **Descrição:** WORC é um jogo de estratégia, onde dois exércitos com tropas únicas se enfrentam até a morte.
* **Gênero:** Tático por turnos (*Turn-based tactics*).
* **Mecânicas:** Dois jogadores se enfrentam comandando exércitos com tropas distintas e habilidades únicas. O objetivo é exterminar o exército inimigo antes de ser exterminado por ele. Cada jogador escolhe um exército de uma das raças do jogo (Orcs, elfos, humanos, etc) e as 10 peças que irão utilizar em batalha, com cada exército contendo 21 tropas distintas.
As tropas variam de tamanho e força conforme de acordo com um ranking de 1-5. O jogador pode pegar uma tropa de Tier 5 e 4, duas de Tier 3 e três de Tier 2 e 1. Havendo três tipos de tropa Tier 5, quatro de Tier 4 e 3, e cinco de Tier 2 e 1.
![Tiers](/assets/images/Tiers.png)
* **Diferencial:** Desde magos a orcs gigantes, **WORC** oferece inúmeras possibilidades e estratégias, o jogador precisa pensar e se adaptar para poder triunfar nos campos de batalha.
* **Plataforma:** Windows 7 ou Superior. 
* **Público alvo:** Jogadores de RPG, jogos de tabuleiro e RTS.
* **Classificação indicativa:** 12 anos – Violência implícita e jogabilidade baseada em estratégia e adaptação.
* **Equipe:** Marcos Eduardo e Vinícius Almeida
* **Jogo de Tabuleiro** *criado por:* Roger Hainz
* **Orçamento:** 
- ***1 exercito + PvP Online*** (09/08/21 - 31/06/22) == *R$ 180.000,00*

***


# **GDD**


![LogoV1 -  WORC](/assets/images/Worc.png)


PC

Classificação: 14+

Data de Lançamento: 30/06/2022

**Escrito por Despause**

Contato[^1][^2][^3]

[^1]: Vinícius Almeida - +55 15 99745-3211
[^2]:Marcos Filho - +55 15 98158-8023
[^3]:despausegamedev@gmail.com

15/11/2021

***


**História e gameplay**

O jogo consiste em uma batalha turno a turno multijogador, entre dois exércitos formados de seres mitológicos e guerreiros lendários, com inspirações no clássico RPG de Fantasia Medieval. 

O objetivo é acabar com todas as tropas do seu inimigo e para isso você tera 1 turno de movimento e 1 turno de ataque, cada um com 5 ações onde você pode mobilizar tropas, usar magias e deferir golpes poderosos para assim alcançar a vitória acabando com o exercíto inimigo.

**Fluxo de jogo**

Ao iniciar uma partida contra um oponente é decidido randomicamente quem jogará primeiro e se inicia a fase de turnos:

* **Pré-Turno**
  Os jogadores alocam as tropas no tabuleiro;
  
* **Turno de Movimento**
  Os jogadores tem 5 ações para movimentar e utilizar habilidades, e ao fim das 5 ações se inicia o turno de ataque;
  
* **Turno de Ataque**
  Os jogadores tem 5 ações para atacar tropas próximas e usar habilidades, ao fim das 5 ações se inicia novamente o turno de movimento.
  
WORC acaba apenas quando um dos jogadores não tem mais tropas no tabuleiro, dando assim a vitória ao exercito remanescente.

**Competitivo**

WORC foi criado para ser um jogo casual e competitivo. Tanto para ser jogado com amigos em uma noite qualquer quanto para o jogador que gosta de aprender as melhores estratégias e se destacar entre os melhores jogadores do mundo.
Os melhores jogadores ao final de cada temporada deverão ser recompensados com itens exclusivos de personalização.

***

**Personagens**

O jogo consta(rá) com vários tipos de tropas diferentes, cada uma delas têm um tipo de poder diferente, sendo essas divididas de Tier 1 à 5. Será necessário administrar suas escolhas para montar uma composição forte.
Você pode, por exemplo, no exército de humanos optar entre uma opção mais estratégica, como um capitão que move todas as suas tropas em sincronia, ou dano bruto, com um mago explodindo bolas de fogo enormes.

![Tropas](/assets/images/Humanos.png)

Cada exército contém 21 tropas distintas. As tropas variam de força conforme de acordo com um Tier de 1-5; entretanto, o jogador pode escolher:
* Uma tropa de Tier 5 e 4;
* Duas de Tier 3;
* Três de Tier 2 e 1. 
Havendo três tipos de tropa Tier 5, quatro de Tier 4 e 3, e cinco de Tier 2 e 1 disponíveis para escolha.

![Tiers](/assets/images/Tiers.png)

A imagem representa a quantidade de tropas diferentes disponíveis por tier, cada círculo verde representa a quantidade máxima possível do tier.
***

**Controles**

O controle do jogo será através de mouse e interface. Clicando em tropas, onde deverá se mover, quem deverá atacar, qual habilidade usará, etc.

**Principais Conceitos do Gameplay**

O jogo é multijogador baseado em partidas, os jogadores escolhem quais raças usarão e iniciam uma partida.

![MMago](/assets/images/Mestre%20mago.png)

Cada linha de informação representa qual será o status da tropa baseando-se na quantidade de pontos de vida, que será utilizado para cálculo de Ataque/Defesa/Movimento, como por exemplo a linha 1 (7 pontos para ataque, 4 para defesa e 4 para movimento). 

Quando é realizado um ataque estes dados são utilizados para calcular a chance de causar dano a um inimigo ou defender-se, sendo 1 ponto de vida o padrão de dano causado.
O alcance para uma tentativa de ataque base é 1, a menos que algum benefício o mude ou seja uma habilidade específica.

Todas as informações presentes tanto nas cartas quanto a descrição das habilidades estarão presentes na informação da tropa, que será acessada através da HUD.

**Cenário**

A adaptação do tabuleiro 12x18 será adaptado numa HUD sobreposta a um cenário para a batalha. Seus “espaços” divididos por quadrados, como um tabuleiro de xadrez.

***

**Mecânicas**

  WORC conta com uma vasta variedade de habilidades e personagens, cada um com mecânicas diferentes, como por exemplo atacar seu inimigo para longe, conjurar raízes, lançar bolas de fogo, transporte de tropas, etc.
  
Seguida das informações de ataque defesa e movimento há a descrição da habilidade. 

![BolaDeFogo](/assets/images/Bola%20de%20fogo.png)

Como descrito, a habilidade bola de fogo por exemplo terá seus números x e y substituídos pela quantidade correspondente ao número atual de vida (Ex: Mestre Mago, com seu máximo de vida: X=5 e Y=5)

As habilidades mais poderosas necessitam de uma ação de preparação (indicado na imagem pelo símbolo antecessor ao nome da habilidade ⓘ) e outra ação para ser executada, ou seja, torna-se necessário dois turnos para o lançamento de uma bola de fogo. Assim que disparada, a habilidade necessita de preparação novamente caso queira usá-la outra vez.

***

**Inteligência Artificial**

  Em Worc utilizamos uma IA baeada em pathfinding, onde ao clicar em um bloco no alcance do movimento da tropa, o jogo encontra o menor caminho entre estes dois pontos respeitando o movimento do tabuleiro (sem andar na diagonal) e coloca-se a fazer o movimento. Também há uma diferenciação nos turnos em Worc, havendo um turno de movimento (onde mesmo que o inimigo esteja no seu alcance, você não poderá ataca-lo) e turno de ataque (onde mesmo que no alcance do seu movimento, você não poderá se movimentar).
