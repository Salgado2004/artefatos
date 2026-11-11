# Padrões em uma Sequência de Resultados

Uma equipe de pesquisa registrou os resultados de um experimento ao longo de vários dias. Para cada dia, foi anotado se o resultado foi considerado **favorável** (V) ou **desfavorável** (D), o horário das medições e o nome do pesquisador responsável.

Analise a sequência abaixo:

|Dia|Resultado|
|---|---|
|1|D|
|2|V|
|3|D|
|4|V|
|5|D|
|6|V|
|7|D|
|8|V|
A partir da observação dos casos apresentados, crie uma função `resultado(n)` que retorne o resultado esperado para qualquer valor positivo de `n`.

Antes de implementar a função, formule uma hipótese que explique o padrão observado.
### Prompts cognitivos

- Quais informações do enunciado parecem relevantes para identificar o padrão?
- É possível prever o resultado do dia 20 sem listar todos os dias anteriores?
- Registre sua hipótese antes de criar a função.
### Self-explanation

- Como você decidiu quais informações ignorar?
- Qual padrão você identificou na sequência?
- Como sua hipótese permite prever novos resultados?
- Sua solução depende de observar todos os casos anteriores? Por quê?