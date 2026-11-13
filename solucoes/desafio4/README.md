# Identificação de Potências de Dois
## Sugestão de Grafo Pandora
![Representação Visual do Grafo Pandora](grafo_programa_desafio4.png)
> O diagrama para o programa Pandora acima pode ser acessado no arquivo [desafio4.json](./desafio4.json).
>
> Para visualizar o grafo, você pode usar a [IDE Web de Pandora](https://example.com). Basta importar o arquivo `desafio4.json` no editor para explorar a estrutura do grafo.

## Explicação
O quarto desafio propõe a criação de uma função que verifica se um número é uma potência de dois. A função `ehPotenciaDeDois(n)` deve retornar "verdadeiro" para números que são potências de dois (como 1, 2, 4, 8, etc.) e "falso" para todos os outros casos, incluindo números negativos e zero.

A lógica para solucionar o problema envolve primeiro identificar os casos base:
- Se `n` for igual a 1, a função retorna "verdadeiro", pois 1 é 2^0.
- Se `n` for igual a 0, a função retorna "falso", pois 0 não é uma potência de dois.
- Se `n` for negativo, a função retorna "falso", pois números negativos não são potências de dois.
- Se `n` for ímpar, a função retorna "falso", pois todas as potências de dois (exceto 1) são pares.

A partir dos casos base, a função pode determinar se `n` é uma potência de dois dividindo-o repetidamente por 2 até que o resultado seja 1 (indicando que `n` é uma potência de dois) ou até que o resultado seja um número ímpar maior que 1 (indicando que `n` não é uma potência de dois).

No grafo Pandora, foi implementada a função auxiliar `ehParPositivo(n)` para verificar se `n` é um número par e positivo, o que ajuda a simplificar a lógica principal da função `ehPotenciaDeDois(n)`.

Inicialmente, a função `ehPotenciaDeDois(n)` verifica se `n` é igual a 1. Se for, retorna "verdadeiro". Caso contrário, chama a função auxiliar `ehParPositivo(n)` para verificar se `n` é par e positivo. Se `n` não for par ou não for positivo, a função retorna "falso". Se `n` for par e positivo, a função divide `n` por 2 e chama a si mesma recursivamente com o novo valor de `n`. Esse processo continua até que `n` seja reduzido a 1 (indicando que é uma potência de dois) ou até que seja determinado que não é uma potência de dois.

## Resultado esperado do desafio
Semelhante ao desafio anterior, o objetivo é que os participantes consigam identificar os subproblemas necessários para resolver o problema principal, implementando a função `ehPotenciaDeDois(n)` corretamente. Além disso, a estrutura do desafio também permite ao participante relacionar a solução ao conhecimento prévio de conceitos matemáticos, como a definição de potências e a decomposição de números em fatores, promovendo uma compreensão mais profunda do problema e da solução.