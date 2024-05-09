# carrinho-de-compras

# Carrinho de Compras e Lista de Tarefas em Java

Este é um projeto simples em Java que implementa duas classes: CarrinhoDeCompras e ListaTarefa. Essas classes permitem gerenciar itens em um carrinho de compras e tarefas em uma lista de tarefas.

## Funcionalidades

### Carrinho de Compras

- Adicionar itens ao carrinho especificando nome, preço e quantidade.
- Remover itens do carrinho pelo nome.
- Calcular o valor total dos itens no carrinho.
- Exibir os itens presentes no carrinho.

### Lista de Tarefas

- Adicionar tarefas à lista especificando uma descrição.
- Remover tarefas da lista pela descrição.
- Obter o número total de tarefas na lista.
- Exibir as descrições de todas as tarefas na lista.

## Utilização

Para utilizar as classes em seu próprio projeto Java, siga estas instruções:

1. Clone ou faça o download deste repositório.
2. Importe as classes CarrinhoDeCompras e ListaTarefa para o seu projeto.
3. Crie uma instância de CarrinhoDeCompras ou ListaTarefa e utilize os métodos disponíveis conforme necessário em seu código.

## Exemplo de Uso

Aqui está um exemplo de como utilizar as classes em seu código:

```java
public static void main(String[] args) {
    // Criando uma instância do carrinho de compras
    CarrinhoDeCompras carrinhoDeCompras = new CarrinhoDeCompras();

    // Adicionando itens ao carrinho
    carrinhoDeCompras.adicionarItem("Lápis", 2d, 3);
    carrinhoDeCompras.adicionarItem("Caderno", 35d, 1);

    // Exibindo os itens no carrinho
    carrinhoDeCompras.exibirItens();

    // Removendo um item do carrinho
    carrinhoDeCompras.removerItem("Lápis");

    // Calculando e exibindo o valor total da compra
    System.out.println("O valor total da compra é = " + carrinhoDeCompras.calcularValorTotal());
}
