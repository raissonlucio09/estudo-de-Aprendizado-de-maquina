# Machine Learning

Aprendizado de máquina é a área em que o sistema aprende padrões a partir de dados, em vez de ser programado com regras explícitas.

## Conceitos
- Supervisionado: dados com rótulo (classificação e regressão)
- Não supervisionado: sem rótulo (agrupamento, ex.: k-means)
- Por reforço: aprende por recompensa e penalidade
- Separação treino/teste e problema de overfitting
- Exemplos: árvores de decisão, k-NN, regressão linear

## Exemplos e lugares aplicados
Prever preço de imóveis, classificar e-mails como spam.

## Minhas anotações da aula
Um sistema de aprendizagem pode adquirir regras de comportamento, descrições de objetos, heurísticas, taxonomias de classificação e outros tipos de conhecimento. Os tipos de aquisição são classificados pela forma de representação do conhecimento:
- Parâmetros em expressões algébricas: ajusta coeficientes numéricos de uma forma funcional fixa. Ex.: o Perceptron de Rosenblatt ajusta pesos para reconhecer padrões.
- Árvores de decisão: os nós são atributos, as arestas são valores dos atributos e as folhas são as classes dos objetos.
- Gramáticas formais: induzem gramáticas (expressões regulares, autômatos finitos, regras de transformação) a partir de expressões de uma linguagem.
- Regras de produção: pares {C → A}; se as condições C forem satisfeitas, as ações A são executadas. São simples de interpretar e muito usadas.
- Expressões baseadas em lógicas formais: descrevem objetos e conceitos usando lógica proposicional ou de predicados.
- Grafos e redes: em alguns domínios são mais expressivos que as expressões lógicas.
- Frames e schemas: representação mais ampla, com entidades rotuladas (slots) que têm papéis predeterminados.
- Taxonomias: hierarquia de classificação obtida por observação.
- Múltiplas representações: combinam diferentes representações para adquirir diferentes formas de conhecimento.
