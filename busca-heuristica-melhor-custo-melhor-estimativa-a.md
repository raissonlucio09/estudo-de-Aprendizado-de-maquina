# Busca Heurística (Melhor Custo, Melhor Estimativa, A*)

Busca heurística usa uma função h(n) que estima o custo do nó atual até o objetivo, guiando a exploração e reduzindo o número de nós visitados.

## Conceitos
- Melhor custo (custo uniforme): expande o nó com menor g(n), o custo já percorrido
- Melhor estimativa (gulosa): expande o nó com menor h(n)
- A*: usa f(n) = g(n) + h(n)
- Heurística admissível (nunca superestima) garante solução ótima no A*

## Exemplos e lugares aplicados
Rotas em mapas usando a distância em linha reta como heurística.

## Minhas anotações da aula
Diferente das buscas cegas, as buscas heurísticas possuem conhecimentos específicos do problema, o que pode levar a soluções mais eficientes do que aquelas que utilizam estratégias sem nenhuma informação.
- A busca gulosa expande o nó mais próximo da meta avaliando os nós apenas com a função heurística f(n) = h(n).
- A busca pelo menor custo também expande o nó mais próximo da meta, mas avalia os nós pela função f(n) = g(n).
- A busca A* expande o nó mais próximo da meta aplicando a função f(n) = g(n) + h(n).
