**Testes de integração testam além do nosso código**
 - Podem testar a integração entre várias classes/módulos da aplicação
 - Podem testar a integração com um sistema externo
     - SGBD (banco de dados)
     - API externa
     - Requisições HTTP para o próprio sistema


 - Não devemos utilizar o banco de dados de produção para realizar testes.
 - Nossos testes devem ser independentes.
 - Transações são nossas amigas ao testar o banco de dados. Devemos realizar todas as operações SQL de um teste dentro de uma transação.
 - O SQLite fornece um banco de dados em memória que pode auxiliar (e muito) na performance da suíte de testes.

**Testes unitários intermediários. utilizar ou não ??**

