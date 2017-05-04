# T7: Algoritmo de Dijkstra com open MPI
## Introdução e Objetivo
O algoritmo de Dijkstra é conhecido na área de computação, por ser um algoritmo que soluciona o problema do menor caminho entre vértices em um grafo. Os vértices são ligados por arestas, na maioria das vezes direcionais, com um peso positivo. Primeiramente escolhe-se um vértice e a partir dele calcula-se o menor caminho para os demais. 

Neste trabalho foi feito uma analogia com cidades, onde busca-se o menor caminho entre todas as cidades. A Figura 1 ilustra um exemplo de um grafo com arestas direcionais do algoritmo de Dijkstra.

![alt text](http://siddarthareddy.weebly.com/uploads/2/8/7/9/28799429/4999443.png?468)

**Figura 1**. Algoritmo de Dijkstra

Neste trabalho você deverá desenvolver uma aplicação paralela utilizando open mpi.

## Desenvolvimento
1. Este trabalho deve ser realizado em **dupla**.
2. Você pode partir do código sequência fornecido em: [Dijkstra.c](https://github.com/fpuntel/C/blob/master/ELC139/Dijkstra/Dijkstra.c). Este programa gera os vértices e arestas de forma aleatória com uma configuração pré-definida, o que facilita para experimentações com grafos de diferentes tamanhos, em algumas partes também possui alguns printfs comentados para auxilio de compreensão do código. Este trabalho está escrito na linguagem C, porm você pode implementar em outra linguagem mantendo a criação do grafo, para facilidade de avaliação.
3. Na paralelização você deve utilizar a biblioteca Open MPI e executar em uma arquitetura fornecida.
4. Para avaliação da sua aplicação paralela deve-se medir os tempos de execuções com diferentes números de processos e tamanhos do grafo. Após isso, deve-se calcular o speedup do seu programa para cada cenário considerado.

## Entrega

O trabalho deve ser entregue até as 23:55 do dia 17/05/2017. Ambos alunos da dupla deve conter no seu repositório **trabalhos/t7** um arquivo nomeado Entrega.md com a seguintes informações:
* Identificação da disciplina, do aluno e da dupla;
* Link para o programa desenvolvido;
* Link para a apresentação com as estratégias de paralelização utilizada, mostrando os experimentos realizados e os resultados obtidos;
* Referências;

## Material de apoio

[Open MPI documentation](https://www.open-mpi.org/doc/)

[MPI Hello World](http://mpitutorial.com/tutorials/mpi-hello-world/)

## Contato

fernandopuntel@gmail.com

skype: fpuntel
