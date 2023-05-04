# TrabalhoMonogame

	Ze Mario

Um grupo de desenvolvedores criou um jogo divertido e desafiante chamado "Ze Mario". Neste artigo,
vamos explicar como o jogo funciona e quais as decisoes foram tomadas para torna-lo um sucesso.

	Introducao
"Ze Mario" e um jogo de plataforma oldschool que mistura elementos de Super Mario e Zelda.
Foi desenvolvido por Luis Moreira, Pedro Saldanha e Rui Cardoso. O jogo apresenta o personagem principal,
Ze Mario, que tem que enfrentar inimigos e superar obstaculos para chegar na bandeira e terminar o jogo.

	Como funciona?
O jogo tem um personagem principal chamado Ze Mario, que tem 4 vidas e pode fazer um DoubleJump.
Ele tem que coletar moedas e derrotar inimigos para vencer o jogo. O jogador usa as teclas de movimento
tradicionais A e D para ir para a esquerda ou para a direita e a barra de espaco para saltar. A tecla F e usada para atacar inimigos.

	Inimigos
Existem tres tipos de inimigos no jogo: Gumba, Planta e Boss.
Gumba: Anda da esquerda para a direita num raio de 3. Se tocar no jogador, o jogador perde uma vida e salta para tras. Tem 100 de HP.
Planta: A sua posicao e fixa. Dispara na direcao do jogador quando este entra no raio de visao dela. Morre com um hit.
Boss: Anda da esquerda para a direita num raio de 3. Salta. Tem uma grande quantidade de vida (500 HP). Musica de Boss.

	Mapas
Existem dois mapas no jogo: Main Menu e Game Map.
Main Menu: O mapa nao e destrutivel. Comeca a tocar a musica de fundo. A plataforma da direita com bandeiras comeca o Game Map. A plataforma da esquerda com picos sai do jogo.
Game Map: O mapa nao e destrutivel. Tem picos que tiram vida ao jogador. Moedas espalhadas para o jogador coletar. Bandeira de checkpoint. Bandeira de final de jogo.

	Informacaoo no ecra
O ecra do jogo mostra a contagem de vidas do jogador e a contagem de moedas coletadas.

	Teclas de Movimento Tradicionais
A -> esquerda
D-> direita
Barra de espaco -> salta
F -> ataque

	Teclas de Configuracao
Esc -> Sai do jogo
J -> Diminui o som do jogo
K -> Aumenta o som do jogo

	Decisoes tomadas
Os desenvolvedores tomaram algumas decisoes ao criar o jogo "Ze Mario".

	Primeira ideia
Inicialmente, o grupo queria criar um jogo de turnos oldschool, como os jogos Final Fantasy e Pokemon. No entanto,
perceberam que isso seria impossivel de realizar com o tempo e conhecimento necessarios. Por isso, optaram por criar
um jogo de plataforma oldschool.

	O jogo
O jogo "Ze Mario" foi criado com inspiracaoo em Super Mario e Zelda. Os desenvolvedores queriam combate no jogo e desafio
nas plataformas. Foram criados tras tipos de inimigos com funcionalidades diferentes.

	O Codigo
O codigo esta em C# que utiliza a biblioteca Microsoft.Xna.Framework e algumas outras bibliotecas externas para
criar um jogo chamado "ZeldaMario". O programa cria uma instancia da classe Game e inicializa varias variaveis 
e objetos, como GraphicsDeviceManager, SpriteBatch e varias listas e texturas.

O programa usa varias classes e metodos fornecidos pelas bibliotecas externas para criar um jogo 2D.
O programa inicializa um mecanismo de fisica usando a biblioteca Genbox.VelcroPhysics.Dynamics, que 
simula a gravidade e outras formas fisicas no mundo do jogo. Ele tambem usa a biblioteca MonoGame 
para criar varios sprites e animacoes, incluindo o personagem do jogador, inimigos, moedas e outros objetos.

O programa carrega varios recursos, incluindo imagens, sons e fontes, usando a classe ContentManager
fornecida pela biblioteca Microsoft.Xna.Framework. Esses recursos sao usados para criar os elementos 
visuais e sonoros do jogo, como o fundo, os movimentos do personagem do jogador e os efeitos sonoros.

O programa tambem inicializa varios objetos que sao usados para gerenciar o estado do jogo e controlar
o fluxo do jogo. Por exemplo, o programa cria um objeto Scene que representa o menu principal do jogo 
e um objeto Flag que representa o final do jogo.

O metodo Update da classe Game e responsavel por atualizar o estado do jogo a cada quadro. 
Isso inclui atualizar o mecanismo de fisica, atualizar a posicao e o estado do personagem do 
jogador e outros objetos e responder as entradas do usuario. O programa tambem verifica colisoes
entre objetos e aciona eventos quando certas condicoes sao atendidas, como o jogador coletar uma moeda ou derrotar um inimigo.

No geral, o programa e um jogo que usa varias bibliotecas e ferramentas.

Grupo: 
Italo 25961
Mario 26530
Gabriel 25242
