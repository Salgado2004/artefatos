# Criando um Filtro Reutilizável
## Sugestão de Grafo Pandora
![Representação Visual do Grafo Pandora](grafo_programa_desafio7.png)
> O diagrama para o programa Pandora acima pode ser acessado no arquivo [desafio7.json](./desafio7.json).
>
> Para visualizar o grafo, você pode usar a [IDE Web de Pandora](https://example.com). Basta importar o arquivo `desafio7.json` no editor para explorar a estrutura do grafo.

## Explicação
O desafio 7 é a continuação direta do desafio 6, mas com uma abordagem que envolve generalização. A função `filtrar(lista, teste)` é projetada para percorrer uma lista e aplicar um critério de seleção definido pela função `teste`. Essa função `teste` recebe um elemento da lista e retorna verdadeiro ou falso, determinando se o elemento deve ser incluído na nova lista resultante.

A vantagem dessa abordagem é que a lógica de filtragem pode ser reutilizada em diferentes contextos, apenas alterando a função `teste` conforme necessário.

Para resolver, o caminho é identificar a estrutura de repetição que percorre a lista e a lógica condicional que decide se um elemento deve ser incluído na nova lista.
- A função `filtrar` é responsável por percorrer a lista até o final, aplicando a função `teste` a cada elemento.
- A função `teste` é responsável por determinar se um elemento deve ser incluído na nova lista, retornando verdadeiro ou falso.

Para exemplificar o uso, o grafo Pandora também incluiu uma função `main` que demonstra a aplicação da função `filtrar` com diferentes critérios de seleção, como números pares e números maiores que 10, conforme os exemplos abaixo:
![Grafo Pandora com Função Main executando filtro com ehPar](./grafo_main_ehPar.png)


![Grafo Pandora com Função Main executando filtro com maiorQue10](./grafo_main_ehMaiorQue10.png)
Em ambos os casos, a função `filtrar` é chamada com a lista de entrada e a função de teste correspondente, resultando em uma nova lista que contém apenas os elementos que atendem ao critério definido.

## Resultado esperado do desafio
Nesse desafio, espera-se que os participantes consigam identificar e reutilizar a lógica de filtragem apresentada, adaptando-a para diferentes critérios de seleção. A função `filtrar(lista, teste)` deve ser capaz de percorrer a lista, aplicar a função `teste` a cada elemento e construir uma nova lista com os elementos que atendem ao critério especificado, demonstrando a compreensão da generalização e da manipulação de listas em um contexto funcional. Além disso, o desafio também apresenta o uso de Funções de Ordem Superior (Ou Primeira Classe, dependendo da literatura) para permitir a passagem de funções como argumentos, promovendo a reutilização e flexibilidade do código.