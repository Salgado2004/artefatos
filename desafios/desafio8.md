# Separação em Duas Listas

Uma central de triagem organiza objetos recebidos em duas caixas: uma para os objetos que atendem a um critério e outra para os que não atendem. A equipe também registra o horário de chegada, o nome do responsável e a localização do depósito, mas a separação depende apenas do teste aplicado a cada objeto.

Crie uma função `separar(lista, teste)` que produza uma lista contendo duas listas aninhadas: a primeira deve reunir os elementos para os quais `teste` retorna verdadeiro, e a segunda deve reunir os demais. Por exemplo, `separar([1, 2, 3, 4], ehPar)` deve produzir `[[2, 4], [1, 3]]`. A função deve preservar a ordem dos elementos e realizar a separação em uma única travessia da lista.
## Prompts cognitivos

- Que estrutura acumulada representa as duas categorias durante a travessia?
- Como preservar a ordem em cada uma das listas aninhadas?
- Teste com números pares e ímpares e com uma lista em que todos os elementos passam ou falham.

## Self-explanation

- Como a função separa o percurso da decisão de classificação?
- Como você garantiu que nenhum elemento foi perdido ou duplicado?
- Por que uma única travessia é suficiente?
- Que relação existe entre `separar` e duas aplicações de `filtrar`?
