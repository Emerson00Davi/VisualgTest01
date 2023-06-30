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
   m : vetor [1..k,1..k] de real <br>
   x,y: inteiro <br>
   s: real <br>

Inicio <br>
   s <- 0 <br>
   aleatorio 1,9 <br>
   para x de 1 ate k faca <br>
      para y de 1 ate k faca <br>
         leia(m[x,y]) <br>
         enquanto ( ( m[x,y] < 1 ) ou ( m[x,y] > 9 )) faca <br>
            leia(m[x,y]) <br>
         fimenquanto<br>
         s <- s + m[x,y] <br>
      fimpara<br>
   fimpara<br>
   aleatorio off <br>
   escreval <br>
   
   para x de 1 ate k faca <br>
      para y de 1 ate k faca <br>
         escreva(m[x,y]:3) <br>
      fimpara <br>
      escreval <br>
   fimpara <br>
   escreval <br>
   
   escreva("A soma é: ", s) <br>
   

         

Fimalgoritmo
