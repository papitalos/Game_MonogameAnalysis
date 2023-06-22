--------------------------------- [English] ---------------------------------
# MonogameProject

	Ze Mario
A group of developers created a fun and challenging game called "Ze Mario." In this article, we will explain how the game works and what decisions were made to make it a success.

	Introduction
"Ze Mario" is an old-school platform game that combines elements from Super Mario and Zelda. It was developed by Luis Moreira, Pedro Saldanha, and Rui Cardoso. The game features the main character, Ze Mario, who has to face enemies and overcome obstacles to reach the flag and finish the game.

	How does it work?
The game has a main character named Ze Mario, who has 4 lives and can perform a DoubleJump. He has to collect coins and defeat enemies to win the game. The player uses the traditional movement keys A and D to move left or right, and the spacebar to jump. The F key is used to attack enemies.

	Enemies
There are three types of enemies in the game: Gumba, Plant, and Boss.
Gumba: Walks from left to right within a radius of 3. If it touches the player, the player loses a life and jumps backward. It has 100 HP.
Plant: Its position is fixed. Shoots in the direction of the player when the player enters its field of view. It dies with one hit.
Boss: Walks from left to right within a radius of 3. Jumps. It has a large amount of health (500 HP). Boss music plays.

	Maps
There are two maps in the game: Main Menu and Game Map.
Main Menu: The map is indestructible. The background music starts playing. The platform on the right with flags leads to the Game Map. The platform on the left with spikes exits the game.
Game Map: The map is indestructible. It has spikes that damage the player's health. Coins are scattered for the player to collect. Checkpoint flag. Game completion flag.

	On-Screen Information
The game screen shows the player's remaining lives and the count of collected coins.

	Traditional Movement Keys
A -> left
D -> right
Spacebar -> jump
F -> attack

	Configuration Keys
Esc -> Quit the game
J -> Decrease game volume
K -> Increase game volume

	Decisions Made
The developers made some decisions when creating the game "Ze Mario."

	First Idea
Initially, the group wanted to create a turn-based old-school game like Final Fantasy and Pokemon. However, they realized that would be impossible to achieve within the required time and knowledge. Therefore, they decided to create an old-school platform game instead.

	The Game
The game "Ze Mario" was created with inspiration from Super Mario and Zelda. The developers wanted combat in the game and challenging platform elements. Three types of enemies were created with different functionalities.

		The Code
The code is written in C#, using the Microsoft.Xna.Framework library and some other external libraries to create a game called "ZeldaMario." The program creates an instance of the Game class and initializes various variables and objects, such as GraphicsDeviceManager, SpriteBatch, and several lists and textures.

The program uses various classes and methods provided by external libraries to create a 2D game. It initializes a physics engine using the Genbox.VelcroPhysics.Dynamics library, which simulates gravity and other physical interactions in the game world. It also uses the MonoGame library to create various sprites and animations, including the player character, enemies, coins, and other objects.

The program loads various resources, including images, sounds, and fonts, using the ContentManager class provided by the Microsoft.Xna.Framework library. These resources are used to create the visual and audio elements of the game, such as the background, player character movements, and sound effects.

The program also initializes several objects that are used to manage the game state and control the game flow. For example, the program creates a Scene object that represents the main menu of the game and a Flag object that represents the game's end.

The Update method of the Game class is responsible for updating the game state each frame. This includes updating the physics engine, updating the position and state of the player character and other objects, and responding to user inputs. The program also checks for collisions between objects and triggers events when certain conditions are met, such as the player collecting a coin or defeating an enemy.

Overall, the program is a game that utilizes multiple libraries and tools.

Group:
Italo 25961
Mario 26530
Gabriel 25242

------------------------------- [Portuguese] -------------------------------
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

	Informacao no ecra
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
