# Trocas-de-Elementos

A execução do código abaixo irá realizar a troca dos elementos de mesma posição entre as duas matrizes:

programa

{

               inclua biblioteca Util

               funcao inicio()

               {

                               inteiro matriz[3][3] = {{1,2,3},{3,4,4},{4,4,4}}

                               inteiro matrizNova[3][3] =  {{1,2,3},{3,4,4},{4,4,4}}

                               para(inteiro x=0;x<Util.numero_linhas(matriz);x++){

                                               para(inteiro y=0;y<Util.numero_colunas(matriz);y++){

                                                               inteiro aux = matriz[x][y]

                                                               matriz[x][y] = matrizNova[x][y]

                                                               matrizNova[x][y] = aux

                                               }

                               }

               }
