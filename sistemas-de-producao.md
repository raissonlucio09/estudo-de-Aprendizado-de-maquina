# Sistemas de Produção

Sistemas de produção representam conhecimento por regras do tipo SE (condição) ENTÃO (ação), executadas por um mecanismo de controle.

 Conceitos
- Base de regras
- Memória de trabalho (fatos atuais)
- Motor de inferência
- Encadeamento para frente (guiado por dados) e para trás (guiado por objetivo)
- Resolução de conflitos entre regras aplicáveis

Exemplos e lugares aplicados
SE febre E tosse ENTÃO suspeita de gripe.

 Minhas anotações da aula
Conhecimento Procedimental x Conhecimento Declarativo

Na representação declarativa o conhecimento é especificado, mas seu uso não é fornecido. Para utilizá-lo é necessário especificar o que deve ser feito com o conhecimento e como. As declarações de implicação definem os caminhos do raciocínio e as declarações atômicas determinam os pontos de partida desses caminhos, de forma parecida com o IF-THEN-ELSE tradicional.

Na representação procedimental, as informações de controle necessárias ao uso do conhecimento estão inseridas no próprio conhecimento. Para isso é necessário um interpretador que siga exatamente as instruções fornecidas.

A grande diferença entre as duas abordagens está em onde residem as informações de controle. Não há consenso sobre qual é melhor; hoje o mais comum é combinar as estruturas de representação de forma flexível.

Os Sistemas de Produção são detalhados no conteúdo de Sistemas Especialistas Baseados em Regras.
