# Caso de Uso: Gerenciar Usuário
## Ator principal: Mantenedor
## Interessados e interesses:
### Mantenedor: 
Deseja incluir, alterar ou remover usuários.

### Administrador: 
Deseja que somente os usuários cadastrados utilizem os elevadores.

### Usuário: 
Deseja ter seus dados atualizados no sistema.

### Pré-condições: 
O mantenedor está logado no sistema.

### Pós-condições: 
Os dados do usuário são inseridos, alterados ou excluídos do sistema.

### Cenário de Sucesso Principal:
1. O mantenedor seleciona a opção de incluir usuário.
2. O mantenedor entra com o nome, andar preferencial, telefone de contato e confirma os dados fornecidos.
4. O sistema realiza a operação.

### Fluxos Alternativos
1a. O mantenedor seleciona a opção de alterar dados do usuário.
  1. O mantenedor modifica os dados.
  2. O sistema armazena as informações em um DB.
1b. O mantenedor seleciona a opção de excluir usuário.
  1. O mantenedor seleciona o usuário a excluir.
  2. O mantenedor confirma a operação de exclusão.
  3. O sistema exclui o usuário do sistema.
