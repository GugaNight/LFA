# LFA
PROJETO DE AUTOMATO
repositorio para a disciplina de linguagem formais e automatos

Instruções de como o projeto deve ser testado

Primeiro deve se criar o variavel que será o aumato e dá lá a quantidade "n" de estados
Ex.: variavel = Automato(n)

Em seguida cadastrar os seus estados colocando o estado atual, o valor do alfabeto e o estado seguinte
exemplo: o estado "q0" com transição com o valor de "A" pra o estado "q1" deverá respeitar a seguinte forma
variavel.cadastrar(0, 'A', 1)

Após cadastrar todas as transições deve indicar o estado final pelo seu estado
Exemplo com "q1" como estado final 
variavel.cadastro_estado_final(1) 

Por fim para testar as palavras, basta digitar e irá printar True para palavras que o automato aceita e False para rejeitado
Ex.: print(variavel.aceitar('ab'))

--------------------------------------------------------------------------------------------------------------------------
PROJETO DE RECONHECEDOR DE PALAVRAS

o arquivo em txt tem que está com os terminais, variaveis e produções especificadas
exemplo 
TERMINAL:
a b c..
VAR:
S A B.. 
PRODU:
S -> A B..

escrever a palavra a testar entre aspas no,
palavra = [(' ',)]
e rodar o programa
