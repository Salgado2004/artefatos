# Caminhos em uma Escadaria

Uma equipe de acessibilidade está estudando diferentes maneiras de subir uma escadaria. Em cada movimento, uma pessoa pode subir:
- 1 degrau; ou
- 2 degraus.

Crie uma função `quantidadeCaminhos(n)` que retorne quantas formas diferentes existem para chegar exatamente ao degrau `n`.

Considere que:
- Existe exatamente 1 maneira de permanecer no degrau 0;
- Existe exatamente 1 maneira de chegar ao degrau 1.
### Exemplos
```
quantidadeCaminhos(0) = 1
quantidadeCaminhos(1) = 1
quantidadeCaminhos(2) = 2
quantidadeCaminhos(3) = 3
quantidadeCaminhos(4) = 5
```

Antes de implementar a função, experimente desenhar ou listar todas as possibilidades para os primeiros valores de `n` e procure identificar um padrão.
### Prompts cognitivos

- Quantas formas existem de alcançar os degraus 0, 1, 2, 3 e 4?
- Para chegar ao degrau `n`, quais podem ter sido os últimos movimentos realizados?
- Como a resposta para um degrau depende das respostas para degraus menores?
- Represente sua estratégia em texto, em um desenho e no grafo Pandora.
- Compare a estrutura desta solução com a contagem recursiva de elementos de uma lista.
### Self-explanation

- Como você identificou os subproblemas necessários para resolver o problema principal?
- Por que toda solução para o degrau `n` depende de soluções para degraus menores?
- Que semelhanças existem entre este desafio e outros problemas recursivos já resolvidos?
- Como você verificou que sua solução funciona para valores pequenos antes de generalizá-la?
- Qual é a regra geral que permite calcular a quantidade de caminhos para qualquer degrau?