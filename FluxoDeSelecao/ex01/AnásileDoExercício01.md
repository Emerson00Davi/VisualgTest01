# EX01

1) Faça um pseudocódigo que preencha um vetor 3x3 com valores aleatórios de 1 a 9

- ENTRADA <br>
  9 números de 1 a 9

- SAÍDA <br>
  A impressão do vetor com os elementos 

- RESTRIÇÕES <br>
  Apenas valores entre 1 e 9

| ENTRADA        |    SAÍDA <br> |
|----------------| --------------|
|1,2,4,5,4,7     |   1,2,4,5,4,7 |


Algoritmo "q1"

const

   k=3

Var
   m : vetor [1..k,1..k] de real
   x,y: inteiro
   s: real

Inicio
   s <- 0
   aleatorio 1,9
   para x de 1 ate k faca
      para y de 1 ate k faca
         leia(m[x,y])
         enquanto ( ( m[x,y] < 1 ) ou ( m[x,y] > 9 )) faca
            leia(m[x,y])
         fimenquanto
         s <- s + m[x,y]
      fimpara
   fimpara
   aleatorio off
   escreval
   
   para x de 1 ate k faca
      para y de 1 ate k faca
         escreva(m[x,y]:3)
      fimpara
      escreval
   fimpara
   escreval
   
   escreva("A soma é: ", s)
   

         

Fimalgoritmo
