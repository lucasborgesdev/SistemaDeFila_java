# SistemaDeFila_java


A fila, é uma forma de pessoas organizarem-se na espera de algum serviço ou
bem. Numa fila, o primeiro a chegar é o primeiro a ser atendido, implementado o
conceito FIFO (Fisrt In, First Out), num caso concreto. Na realidade o primeiro a
chegar, sendo o primeiro a ser atendido, guarda-se o conceito de civilidade e direito,
que só pode ser subvertido por meio de lei, que o caso da lei brasileira (Decreto-Lei
n.º 135/99, de 22 de Abril) que manda que alguns cidadãos em especial tenham
direito maior que os do que outros que chegaram anteriormente.
Problema a ser resolvido:
De acordo com os conteúdos ministrados em sala de aula, faça um programa em Java
que baseando-se em um vetor, controle uma fila de pessoas a serem atendidas.
Deseja-se controlar a fila apenas com o primeiro nome das pessoas. Para este
programa, não é necessário implementar atendimento especial/prioritário. Para isso,
torne funcional o seguinte menu de opções:
Menu:

1 – Cadastrar nova pessoa na fila
2 – Chamar o próximo da fila
3 – Listar todos que ainda estão aguardando atendimento
4 – Sair

Dica: armazene os nomes das pessoas em um vetor de String. Crie duas variáveis
auxiliares, uma para guardar o índice do início da fila e outra para guardar o índice do
final da fila. Conforme forem chegando novas pessoas ou que forem sendo atendidas,
mude os valores das variáveis auxiliares.
Exemplo:

A fila com 3 pessoas poderia ser assim representada:
0 1 2 3 4 5 6
Maria Pedro Paulo
A variável auxiliar de início valeria 0.
A variável auxiliar de fim valeria 2.
Ao chegar uma nova pessoa, basta guardar o nome na posição fim + 1 do vetor e
atualizar o valor da variável de fim:
0 1 2 3 4 5 6
Maria Pedro Paulo Joãozinho
A variável auxiliar de início valeria 0.
A variável auxiliar de fim valeria 3.
Ao chamar o próximo da fila, poderíamos pegar o valor que está na posição de início
e mostrar na tela, que no caso seria a Maria. E em seguida incrementar o valor da
variável inicio. Ficando desta forma a organização
0 1 2 3 4 5 6
Maria Pedro Paulo Joãozinho
A variável auxiliar de início valeria 1.
A variável auxiliar de fim valeria 3.
Se neste momento for selecionada a opção de listar pessoas na fila, mostramos desde
o índice de início até o índice de fim. Assim, no exemplo em questão, mostraríamos:
• Pedro
• Paulo
• Joãozinho
