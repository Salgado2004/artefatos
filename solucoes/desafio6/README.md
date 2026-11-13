# Remoção Seletiva de Elementos
## Sugestão de Grafo Pandora
![Representação Visual do Grafo Pandora](grafo_programa_desafio6.png)
> O diagrama para o programa Pandora acima pode ser acessado no arquivo [desafio6.json](./desafio6.json).
>
> Para visualizar o grafo, você pode usar a [IDE Web de Pandora](https://example.com). Basta importar o arquivo `desafio6.json` no editor para explorar a estrutura do grafo.

## Explicação
O desafio 6 consiste na criação de uma função `removerElemento(lista, elemento)` que remove todas as ocorrências de um determinado elemento de uma lista, utilizando uma abordagem recursiva. A função deve ser capaz de lidar com listas vazias e listas com qualquer quantidade de elementos, sem receber previamente essa quantidade.

A estrutura inicial da função inicia da mesma forma que a função do desafio 2, verificando se a lista está vazia. Caso esteja, retorna uma lista vazia. Caso contrário, chama a si mesma com o restante da lista, utilizando `tail`, até que atinge o caso base. A diferença é que, ao invés de contar os elementos, a função verifica se o primeiro elemento da lista é igual ao elemento a ser removido. Se for, ele não é incluído na lista resultante; caso contrário, ele é adicionado à lista resultante.

Como resultado, a função percorre todos os elementos da lista, aplicando a mesma lógica recursiva até atingir o caso base, e então retorna uma nova lista sem as ocorrências do elemento especificado.

Como o nós de inclusão de elementos (`cons`) insere o elemento no início da lista, a inserção dos elementos na lista resultante ocorre de forma reversa, a partir do caso base, garantindo que a ordem dos elementos na lista final seja preservada.

## Resultado esperado do desafio
Ao realizar o desafio, espera-se que os participantes consigam identificar e reutilizar a lógica recursiva apresentada no desafio 2, adaptando-a para remover elementos de uma lista. A função `removerElemento(lista, elemento)` deve ser capaz de percorrer a lista, verificar cada elemento e construir uma nova lista sem as ocorrências do elemento especificado, demonstrando a compreensão da recursão e da manipulação de listas em um contexto funcional.