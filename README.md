# LFA
repositorio para a disciplina de linguagem formais e automatos


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
