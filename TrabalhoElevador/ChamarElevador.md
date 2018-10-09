# Caso de Uso: Chamar Elevador
## Ator principal: Usuário final
## Interessados e interesses:
### Usuário:
Deseja utilizar o elevador.

### Administrador:
Deseja construir um sistema que facilite o uso dos elevadores do prédio.

### Porteiro:
Deseja que as viagens dos usuários sejam armazenadas em uma Data Base.

### Pré-condições:
O usuário possui um cartão de acesso.

### Pós-condições:
O usuário é atendido com o elevador que o leva ao andar correspondente ao solicitado.

### Cenário de Sucesso Principal:
1.O usuário insere o card no painel de acesso.
2.O sistema verifica a validade do card localiza o usuário.
3.O sistema exibe o andar preferencial do usuário.
4.O usuário confirma o andar sugerido.
5.O sistema informa o elevador a ser tomado.
6.O usuário se dirige ao elevador informado.

### Fluxos Alternativos:
2. O card utilizado está em situação de não conformidade ou com defeito.
  •O sistema informa que a validade expirou.
  •O usuário se dirige ao mantenedor para regularizar o card. 
3. O usuário deseja ir a outro andar que não o preferencial.
  •O usuário informa o andar desejado no painel do EI.
5.Todos os elevadores estão cheios.
  •O sistema pede ao usuário que aguarde. 
6. O elevador informado está cheio.
  •O usuário retorna ao painel de acesso e solicita outro elevador.
