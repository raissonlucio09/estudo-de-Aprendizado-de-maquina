# Sistemas Especialistas Baseados em Casos

O raciocínio baseado em casos (CBR) resolve novos problemas reaproveitando soluções de problemas parecidos já resolvidos.

Conceitos
- Base de casos (problema + solução)
- Ciclo dos 4 Rs: recuperar, reutilizar, revisar e reter
- Medida de similaridade para achar o caso mais próximo
- Não exige regras explícitas

Exemplos e lugares aplicados
Help desk que sugere soluções de chamados anteriores.

 Minhas anotações da aula
- Os Sistemas Especialistas Baseados em Casos não requerem um modelo de domínio explícito. Por isso, a elicitação vira uma tarefa de agregar histórico de casos, a implementação se reduz a identificar características significativas que descrevem um caso, e o sistema aprende adquirindo novos conhecimentos como casos.
- Fases do ciclo de vida de um RBC:
  1. RECUPERAR o caso mais similar
  2. REUTILIZAR o caso para tentar resolver o problema atual
  3. REVISAR a solução proposta, se necessário
  4. RETER a nova solução como parte de um novo caso
