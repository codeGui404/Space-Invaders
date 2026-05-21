👾 Space Invaders - Python + Pygame
Projeto desenvolvido em Python utilizando a biblioteca Pygame, inspirado no clássico jogo arcade Space Invaders.

O jogo possui:

movimentação do jogador;
sistema de tiros;
inimigos com movimentação dinâmica;
nave especial;
sistema de colisão;
obstáculos destrutíveis;
pontuação;
sons;
interface arcade clássica.
🚀 Tecnologias Utilizadas
Python 3
Pygame
Programação Orientada a Objetos (POO)
Sistema de Sprites
Eventos do Pygame
Sistema de colisão
Sons e efeitos
📂 Estrutura do Projeto
Space_Invaders/
│
├── Main.py
├── game.py
├── spaceship.py
├── alien.py
├── laser.py
├── obstaculo.py
│
├── Font/
│   └── monogram.ttf
│
├── Imagens/
│   ├── spaceship.png
│   ├── alien_1.png
│   ├── alien_2.png
│   ├── alien_3.png
│   └── mystery.png
│
├── Sounds/
│   ├── laser.ogg
│   ├── explosion.ogg
│   └── music.ogg
│
└── README.md
🧠 Arquitetura do Projeto
O projeto foi dividido em múltiplos arquivos para facilitar:

organização;
manutenção;
reutilização de código;
escalabilidade;
legibilidade.
Responsabilidade de cada arquivo
Arquivo	Responsabilidade
Main.py	Loop principal do jogo
game.py	Regras e lógica principal
spaceship.py	Jogador
alien.py	Inimigos e nave especial
laser.py	Sistema de tiros
obstaculo.py	Barreiras defensivas
⚙️ Pré-requisitos
Antes de executar o projeto, você precisa ter instalado:

✅ Python 3
Verifique se possui o Python instalado:

python --version
ou:

python3 --version
Caso não tenha:

🔗 https://www.python.org/downloads/

📦 Instalação do Pygame
Instale o Pygame utilizando:

pip install pygame
ou:

pip3 install pygame
▶️ Como Executar o Projeto
Execute o arquivo principal:

python Main.py
ou:

python3 Main.py
🎮 Controles do Jogo
Tecla	Ação
⬅️	Mover para esquerda
➡️	Mover para direita
SPACE	Atirar
ESC	Fechar o jogo
👾 Mecânicas Implementadas
🚀 Nave do jogador
movimentação lateral;
limite de tela;
cooldown de tiro;
sistema de vidas.
👾 Inimigos
movimentação coletiva;
mudança de direção;
descida progressiva;
tiros aleatórios.
🛸 Nave especial
aparece aleatoriamente;
movimentação dinâmica;
pontuação bônus.
🧱 Obstáculos
barreiras destrutíveis;
sistema baseado em grid;
colisão com tiros.
🔫 Sistema de tiros
tiros do jogador;
tiros dos inimigos;
colisão entre sprites;
remoção automática fora da tela.
🔊 Sons
efeitos sonoros;
música de fundo;
sons de disparo e explosão.
🧩 Conceitos Utilizados
O projeto utiliza diversos conceitos importantes de desenvolvimento de jogos:

Programação Orientada a Objetos;
Game Loop;
Sprites;
Sprite Groups;
Eventos;
Timers;
Colisões;
Renderização;
Manipulação de áudio;
Controle de FPS.
🏗️ Como Funciona o Game Loop
O jogo funciona através de um loop principal infinito:

while True:
Esse loop:

captura eventos;
atualiza entidades;
processa colisões;
desenha elementos na tela;
atualiza o display.
Tudo isso ocorre aproximadamente:

60 FPS
📚 Aprendizados Demonstrados no Projeto
Esse projeto demonstra conhecimento em:

arquitetura de software;
orientação a objetos;
manipulação de eventos;
lógica de jogos;
gerenciamento de sprites;
controle de estado;
timers;
modularização;
organização de código.
