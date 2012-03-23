Exercícios realizados na pós:
============================

## Primeira aula, 22/03/2012
No primeiro dia de aula, o professor iniciou os alunos no mundo <code>java</code>, mostrando de uma forma básica como tudo funciona, e ao final na aula, criou um pequeno programa que gerava uma mensagem que eu não lembro, então resolvi fazer o famoso "Alô Mundo".

A cada nova aula eu pretendo publicar no meu <code>git</code> tudo que foi passado, desse modo eu amplio o meu conhecimento  e também compartilho, apesar da maioria dos exercícios serem muito básicos, podem servir para algum estudante iniciante.

* Para compilar o arquivo e bem fácil:
	
	javac Alo.java

Caso o <code>javac</code> não tenha gerado nenhum mensagem, o arquivo deve ter sido compilado com sucesso. Após executar esse comando o um novo arquivo é criado, <code>Alo.class</code>. 

* Para executar o programa basta digitar:
	
 	java Alo

Não é necessário colocar a extenção no arquivo, caso seja colocado, um <code>exception</code> e gerado pelo <code>java</code>.
	
O <code>java</code> possui suporte a geração de documento, com base nos comentários que são feitos no código, e mesmo que nenhum comentário seja feito, também é possível gerar a documentação, como pode ser visto no exercício [alo-mundo](https://github.com/riquellopes/exercicios-pos/tree/master/alo-mundo).

 * Para gerar a documentação:
	
	javadoc Alo.java