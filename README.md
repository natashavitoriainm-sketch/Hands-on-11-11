# Hands on - 11/11

1. Crie um programa em Java que:
   1. Crie uma lista de compras usando `ArrayList`.
   2. Adicione 5 produtos.
   3. Mostre todos os produtos cadastrados.
   4. Mostre a quantidade total de produtos.
2. Crie um programa que:
   1. Crie um `ArrayList<Double>` para armazenar notas.
   2. Adicione 4 notas.
   3. Calcule a média.
   4. Mostre se a turma ficou com média maior ou igual a 7.
3. Crie uma classe `Livro` com:

   * Código
   * Título
   * Autor
   * Disponível

   Depois, crie um sistema com menu:

   ```java
   1 - Cadastrar livro
   2 - Listar livros
   3 - Emprestar livro
   4 - Devolver livro
   0 - Sair
   ```

   Regras:

   * Um livro só pode ser emprestado se estiver disponível.
   * Ao emprestar, o status deve mudar para indisponível.
   * Ao devolver, o status deve mudar para disponível.
   * Use `ArrayList<Livro>`.
4. Crie um sistema em Java para controlar pedidos de uma lanchonete.

   O sistema deve possuir uma classe `Pedido` com:

   * Número do pedido
   * Nome do cliente
   * Item pedido
   * Valor
   * Status

   O status pode ser:

   ```java
   PENDENTE
   PREPARANDO
   FINALIZADO
   ```

   O sistema deve permitir:

   ```java
   1 - Cadastrar pedido
   2 - Listar pedidos
   3 - Atualizar status de um pedido
   4 - Buscar pedido pelo número
   5 - Mostrar valor total dos pedidos
   0 - Sair
   ```
