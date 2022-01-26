# DictionaryTreeC

Algoritmo em linguagem C que armazena palavras em uma árvore.

Cada nó possui:

- Um variável char que guarda um char.
- Uma variável boolean que indica que aquela letra é o fim de uma palavra.
- Um vetor com 26 ponteiros, onde cada ponteiro aponta para a próxima letra de uma possivel palavra. 

Abaixo segue uma representação visual de como as palavras abacate e abacaxi seriam armazenadas nessa árvore. 

          ABACATE
               \
                 XI
