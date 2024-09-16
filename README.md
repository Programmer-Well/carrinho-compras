# Carrinho de Compras

Este é um projeto simples de um carrinho de compras implementado com HTML, CSS e JavaScript.

## Funcionalidades

- **Adicionar Produtos:** Permite adicionar produtos ao carrinho, selecionando-os em um menu dropdown e especificando a quantidade.
- **Calcular Total:** Calcula automaticamente o preço total dos produtos no carrinho.
- **Limpar Carrinho:** Remove todos os produtos do carrinho e redefine o total para zero.

## Estrutura do Código

**HTML (index.html):**

- Define a estrutura básica da página, incluindo:
    - Um formulário para adicionar produtos ao carrinho.
    - Uma seção para exibir os produtos no carrinho e o total.

**CSS (style.css):**

- Estiliza os elementos da página, proporcionando uma aparência visualmente agradável.

**JavaScript (app.js):**

- Contém as funções JavaScript que implementam as funcionalidades do carrinho:
    - `adicionar()`:
        - Obtém os detalhes do produto (nome, preço unitário) e a quantidade selecionada pelo usuário.
        - Calcula o preço total do item (quantidade * preço unitário).
        - Adiciona uma nova linha à seção do carrinho, exibindo os detalhes do item adicionado.
        - Atualiza o total geral do carrinho.
    - `limpar()`:
        - Remove todos os itens do carrinho.
        - Redefine o total geral para zero.

## Como Usar

1. https://carrinho-compras-js-five.vercel.app/ 

