# Generalização de Potências

Uma estação de pesquisa organiza amostras em recipientes cujo número deve ser uma potência de uma base escolhida para cada experimento. Em um experimento, as bases possíveis são números inteiros maiores ou iguais a 2.

A partir da estratégia usada em `ehPotenciaDeDois`, crie uma função `ehPotencia(n, base)` que retorne verdadeiro quando existir um inteiro `k` tal que `n = base^k`. Considere `n` positivo, `base >= 2` e que `1` é uma potência de toda base válida.
## Prompts cognitivos

- O que na solução anterior era uma característica específica do número dois?
- Que informação precisa se tornar um parâmetro?
- Qual parte da estratégia permanece igual para qualquer base?
- Compare as soluções para base 2 e base 3 com os mesmos valores de entrada.
- Represente a transformação de uma função específica em uma função geral.
- Teste casos como `(1, 2)`, `(8, 2)`, `(9, 3)`, `(12, 2)` e `(10, 3)`.
## Self-explanation

- O que foi generalizado e o que permaneceu inalterado?
- Por que a base deve ser maior ou igual a 2?
- Como sua solução trata o caso `n = 1`?