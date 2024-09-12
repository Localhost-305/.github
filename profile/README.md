# Padrões de commits 📜

O commit semântico possui os elementos estruturais abaixo, exemplo de nova feature: 
`git commit -m 'feature/LOC-01/adicionando funcionalidade X`:

- `feature`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

# Padrões de branch 📜

O padrão da criação da branch é a `ação/loc-Número da task`, exemplo de nova branch: 

- task 01 - Cadastro e visualização do usuário
- branch - feature/LOC-01/
