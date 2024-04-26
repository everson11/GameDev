Integrantes: Everson Bendedetti e Eduardo Coltro
Jogo 2D com 2 fazes de jogatina criado utilizando movimento, pulo, inimigos e armadilhas para criar uma experiência desafiadora e envolvente. 

# Como jogar:
Instalar o GIT > Copiar o link do repositório > git clone “link do repositório”.
Abrir o projeto em seu Unity, utilizando a versão 2021.3.

# Principais mecânicas desenvolvidas:

Mecânica de Andar e Pular:

O jogador pode se movimentar horizontalmente utilizando as teclas de direção ou as teclas W, A, S, D no teclado. Além disso, é possível realizar pulos para superar obstáculos e evitar inimigos. Essas mecânicas são fundamentais para explorar o ambiente do jogo, superar desafios e avançar pelas fases.

GameManager:

Gerencia o fluxo do jogo, controlando transições entre cenas.

Inimigos:

Este script controla o movimento de inimigos ao longo de um caminho definido. 

Mola:

Este script controla o comportamento de uma mola, quando o jogador entra em contato com a mola ativa uma animação de subida e impulsiona o jogador para cima com uma força especificada.

Armadilha:

Este script controla o comportamento de uma plataforma armadilha quando ativado, ele reproduz uma animação de parada e, após um certo período de tempo, causa uma explosão e destrói a plataforma.

Obs: Algumas funcionalidades não estão 100%. 
