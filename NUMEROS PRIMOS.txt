Algoritmo "NUMEROS PRIMOS"
//
//
// Descrição   : ATRAVES DE UM NUMERO POSTOS PELO USUARIO ELE E SEPARADO POR
//NUMEROS PRIMOS E SOMADOS.
// Autor(a)    : Wanderson Luis Conceicao de Souza
// Data atual  : 24/05/2022
Var
//C=CONTADOR 1, CC=CONTADOR-2, N=NUMERO, P=PRIMOS E S=SOMATORIO
    c,cc,n,p:inteiro
    s:real

Inicio
// AQUI O USUARIO DIGITARA UM NUMERO

     escreva("Digite ate que numero primo quer a contagem:")
     leia(n)
     
 // AQUI É ONDE OCORRE A VERIFICACAO DOS ANTECESSORES DESSE NUMERO PRIMO E EXIBI
 
     s<-0
     
     para c de 1 ate n faca
     p<-0
      para cc de 1 ate c faca
         se(c mod cc=0)entao
           p<-p+1
       fimse
     fimpara
       se (p=2)entao
     escreval("O numero", c , " é primo")

//A SOMATORIA DOS NUMEROS PRIMOS

       s<-(s + c)
    fimse
    fimpara
         escreval(" ")
         escreva(" A soma dos numeros primos é: ", s)


Fimalgoritmo