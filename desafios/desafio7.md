# Criando um Filtro Reutilizável

Uma equipe de análise precisa selecionar dados de naturezas diferentes. Em um relatório, deseja manter números pares; em outro, números perfeitos (em que soma a de seus divisores próprios corresponde ao seu valor. `Ex. 6: 1 + 2 + 3 = 6`) . Os relatórios também contêm datas, autores, cores e identificadores, mas cada seleção deve considerar apenas o teste definido para seus elementos.

Sem usar uma operação nativa de filtragem, crie uma função `filtrar(lista, teste)`. A função `teste` recebe um elemento e retorna verdadeiro ou falso. `filtrar` deve percorrer a lista e produzir uma nova lista apenas com os elementos para os quais `teste` retorna verdadeiro. Use a mesma função para filtrar números pares e números perfeitos. Depois, crie um terceiro teste escolhido por você.
## Prompts cognitivos

- O que é igual nos dois exemplos de filtragem?
- Qual parte da solução percorre a lista?
- Qual parte decide se um elemento permanece?
- Teste a mesma implementação com listas vazias, listas sem correspondências
  e listas em que todos os elementos passam no teste.
## Self-explanation

- Como a solução separa o mecanismo de percurso do critério de seleção?
- Que parte da implementação precisou ser escrita uma única vez?
- Qual foi o seu terceiro teste e por que a implementação não precisou ser
  modificada para usá-lo?
