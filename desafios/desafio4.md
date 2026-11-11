# Identificação de Potências de Dois

Uma empresa de iluminação organiza seus equipamentos em grupos cujo tamanho deve dobrar a cada etapa: 1, 2, 4, 8 e assim por diante. O inventário também registra o fabricante, a cor das lâmpadas e a data de compra.

Crie uma função `ehPotenciaDeDois(n)` que retorne verdadeiro quando `n` for uma potência inteira de dois e falso nos demais casos. Considere como potências de dois os valores `1`, `2`, `4`, `8` e os valores obtidos continuamente pela multiplicação por dois. A solução deve tratar valores positivos, zero e valores negativos.
## Prompts cognitivos

- Qual é o caso mais simples que deve ser aceito?
- O que acontece com `n` quando ele é dividido por dois?
- Como distinguir um valor que pode continuar a ser dividido de um valor que
  já não pertence à sequência?
- Quais casos devem ser rejeitados imediatamente?
- Descreva a estratégia usando uma função que chama uma versão menor do mesmo
  problema.
## Self-explanation

- Como sua solução identifica que um número não pode ser potência de dois?
- Qual é o caso-base e qual é o caso recursivo?
- Que parte da solução depende especificamente da base dois?
