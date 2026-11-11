# Remoção Seletiva de Elementos

Uma curadora está preparando uma lista de peças para uma exposição. Algumas peças foram retiradas por apresentarem uma etiqueta específica, e a lista final deve preservar a ordem das peças restantes. O relatório também contém o material, o peso e a sala de cada peça, mas somente o valor da etiqueta deve ser usado na remoção.

Crie uma função `removerElementos(lista, valor)` que produza uma nova lista contendo os elementos da lista original, exceto aqueles iguais a `valor`. Por exemplo, `removerElementos([1, 3, 2, 3, 4], 3)` deve produzir `[1, 2, 4]`. Considere que a lista original não deve ser alterada.
## Prompts cognitivos

- O que deve ser retornado quando a lista estiver vazia?
- O que fazer quando o primeiro elemento for igual ao valor procurado?
- O que fazer quando ele for diferente?
- Como preservar a ordem dos elementos que permanecem?
## Self-explanation

- Como sua solução decide entre manter e descartar um elemento?
- Por que o restante da lista precisa ser processado nos dois casos?
- Qual parte da solução é específica para comparar com um único valor?
