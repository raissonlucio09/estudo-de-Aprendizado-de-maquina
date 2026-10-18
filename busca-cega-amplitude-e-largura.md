# Busca Cega (Amplitude e Largura)

Busca cega (não informada) explora o espaço de estados sem usar nenhuma informação sobre a distância até o objetivo. Amplitude e largura se referem à busca em largura (BFS), que expande os nós nível por nível usando uma fila.

Conceitos
- Busca em largura (BFS): usa fila, completa, encontra o caminho com menos passos
- Alto consumo de memória
- Busca em profundidade (DFS): usa pilha, pouca memória, pode não achar o melhor caminho
- Critérios: completude, otimalidade, complexidade de tempo e espaço

 Exemplos e lugares aplicados
Encontrar o caminho mais curto em um labirinto ou grafo sem pesos.

Minhas anotações da aula
Uma Busca Cega é caracterizada por uma busca sem informação, ou seja, ela não recebe nenhuma informação sobre o problema além da sua própria definição.
- A Busca em Extensão é uma busca simples em que o nó raiz é expandido primeiro, em seguida todos os sucessores do nó raiz são expandidos, depois os sucessores desses nós e assim por diante.
- A Busca em Profundidade se caracteriza pela expansão do nó mais profundo na borda atual da árvore de busca. A busca prossegue imediatamente até o nível mais profundo da árvore de busca, onde os nós não têm mais sucessores.
