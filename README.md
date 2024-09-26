# Algoritmo de Kruskal e sua aplicação em Redes de computadores

  Neste trabalho estaremos realizando a implementação do algoritmo de Kruskal e o seu devido estudo aplicado à uma rede de computadores de acordo com o paper [Application of Graph Theory to Computer Networks Using the Kruskal Algorithm](https://www.researchgate.net/profile/Putri-Indah-Pramesti/publication/381519447_Application_of_Graph_Theory_to_Computer_Networks_Using_the_Kruskal_Algorithm/data/66726682a54c5f0b946e2804/Application-of-Graph-Theory-to-Computer-Networks-Using-the-Kruskal-Algorithm.pdf)

## Participantes
- Adriel
- Ana
- Pedro
- Luan

## Índice

  - [Roteiro do Trabalho](#roteiro-do-trabalho)
    - [Gerar Grafos](#gerar-grafos)
    - [Matriz Adjacência](#matriz-adjacencia)
    - [Matriz Custo](#matriz-custo)
    - [Algoritmo de Kruskal](#algoritmo-de-kruskal)
    - [Complexidade do Grafo](#complexidade-do-grafo)
    - [Desenho dos Grafos](#desenho-dos-grafos)
    - [Krukal em Redes de Computadores](#kruskal-em-redes-de-computadores)
  - [Implementação](#implementacao)
    - [Google Colab](#google-colab)
    - [Bibliotecas usadas](#bibliotecas-usadas)
  

## Roteiro do Trabalho

### Gerar Grafos

  Gerar grafos simples e conexos com n=10, 50 e 100
    - Grafo simples: um grafo que não possui laços (arestas que conectam um nó a ele mesmo) nem múltiplas arestas entre os mesmos pares de nós.
    - Grafo conexo: é um grafo onde há pelo menos um caminho entre cada par de nós.
    - n representa o número de nós (vértices) no grafo.

### Matriz Adjacência

  - Gerar a Matriz Adjacência
  - A matriz de adjacência é uma forma de representar um grafo onde cada linha e coluna da matriz representam um vértice. Se houver uma aresta entre o vértice i e o vértice j, o valor na posição 𝐴[i][j] será 1 (ou o peso da aresta, no caso de grafos ponderados), e 0 se não houver aresta.
    
### Matriz Custo

  - Gerar uma matriz de custo
  - A Matriz de Custo é semelhante à matriz de adjacência, mas ao invés de marcar apenas a existência de arestas, você atribui um custo a cada aresta. Nesse caso, os custos devem ser números inteiros no intervalo de 1 a 5

### Algoritmo de Kruskal

  Aqui, realizaremos a implementação do Algoritmo de Kruskal para encontrar árvores geradoras mínimas

### Complexidade do Grafo
  Vamos analizar uma análise teória usando a notagem Grande O para definir a complexidade de tempo e de entradas do Algoritmo de Kruskal
      
### Desenho dos Grafos
  Vamos estar utilizando pandas, networkx e matplotlib para a plotagem dos grafos

### Krukal em Redes de Computadores

Por fim, estudaremos a aplicação do Kruskal em Redes de Computadores

## Implementação
      
### Google Colab
  Utilizamos notebooks no Google Colab como Plataforma de Desenvolvimento para desenvolver esse trabalho

### Bibliotecas Usadas
  Usamos as seguintes bibliotecas:
      - networkx para criação e manipulação de grafos
      - matplotlib.pyplot para plotagem de grafos
      - random para geração de números aleatórios
      - pandas para criação e uso de Dataframes
      - numpy para realização de operações matemáticas

