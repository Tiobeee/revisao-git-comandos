# Branchs
São ramificações do projeto, o qual permite vários desenvolvedores, trabalharem em diferentes funcionalidades, sem bugar a versão estável.

##  Principais branchs
Branch main -> que é a branch principal, ou seja, a branch estável da aplicação. Versão que é disponibilizada aos clientes.

Branch developer -> É a branch utilizada pelos testers. Os quais vão testar as novas funcionalidades, correções de bugs, etc.

## Outras branchs
Para cada nova funcionalidade ou correção de bugs é criada uma nova branch.

### Padrôes para criar nomes de branchs
!IMPORTANTE! Nomes de branchs não tem acento nem Ç  
Para correções de bugs: fix_identificacao_do_bug
Exemplo: fix_botao_de_login, fix_cor_do_cabecalho

Para novas funcionalidades:
feat_identificacao_da_nova_funcionalidade
Exemplo: feat_integracao_com_google, feat_nova_tela_de_contato

Para atualizar documentação: chore_identificacao_da_alteracao
Exemplo: doc_adicionada_nova_imagem

Para criação/alteração de tarefas que não interferem no código:
chore_identificacao_da_modificacao
Exemplo: chore_atualizado_a_versao_do_banco

## Comandos para trabalhar com branchs
### Criação de novas branchs
git checkout -b nome_da_nova_branch
Exemplo: git checkout -b fix_botao_da_tela_login
OBS: O ideal é sempre criar as branchs a partir da main

### Listar as branchs existentes
git branch list

### Trocar de branch
git switch nome_da_branch_que_deseja_entrar
Exemplo 01: git switch fix_botao_da_tela_login
Exemplo 02: git switch main

### Excluir uma branch
git branch -D nome_da_branch_que_deseja_excluir
Exemplo: git branch -D fix_botao_da_tela_login