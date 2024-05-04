Este foi uma atividade da disciplina de Estrutura de Dados, ministrada pelo professor Alechandre Ichiro Hasimoto, curso de Ciência de Dados, da Fatec Cotia.
O exercício proposto foi a criação de um código para o famoso "Jogo da Velha", a fim de trabalharmos com matrizes.
Minha atividade foi a estruturação da lógica e um script para trabalhar em conjunto com o ChatGPT. 
Abaixo as instruções que formulei e passei a ele, onde tive uma assertividade grande com o que eu queria. O código em anexo foi a primeira resposta dele.
Instruções para o Jogo Da Nova, texto em Python:
"""
Estou criando um jogo. Não precisa associar a jogos existentes, considere como um novo jogo e siga os passos para a criação.
O nome do jogo é "Jogo da nova"
1 - matriz 3x preenchidas de um espaço vazio " "
2 - mostre a matriz em tela
3 - dois jogadores, cada um faz um input ("Sua vez") de uma vez, com random para saber qual é o primeiro
4 - o input é "X" para um jogador e "O" para o outro, a definição de qual é qual, é através de random tambem
5 - print em tela qual é o primeiro a jogar e qual o seu simbolo (no caso a letra "O" ou "X")
6 - No input o jogador diz qual é a posição da jogada (i,j) 
7 - não pode jogar na mesma posição, caso contrário ("Essa posição já esta preenchida")
8 - A partir da quinta rodada no geral verifique, 
	- se alguma dessas posições da matriz ((11,21,31), (12,22,32), (13,23,33), (11,12,13), (21,22,23), (31,32,33), (11,22,33), (31,22,13)), estiverem preenchidas somente com "X" ou somente com "O", o jogador responsável pelo simbolo vence. Imprima a matriz e print (f"O jogador {jogador} venceu!")
	- else o jogo continua.
9 - Continua até todas as casas da Matriz estiverem preenchidas, print "Ih, o jogo deu Nova.". Ou seja, empate.
10 - Recomeça o Jogo.
"""
