# Curso Digital: Git/Versionamento

## Comandos Git

### Log
* Comando git log - Exibe todo o histórico de alterações.

* Comando git log --oneline --decorate - Indica um hitórico de commits e também indica em que branche está o ponteiro HEAD. 

### Manipular arquivos/diretórios
* Comando git push - O primeiro push de um repositório deve conter o nome do repositório remoto (origin) e o branch (main). Os demais pushes não precisam dessa informação.

* Comando git pull - Recupera e baixa o conteúdo de um repositório remoto e atualiza o repositório local assim que ele for baixado.

* Comando git fetch - Busca as alterações realizadas mas não as aplica ao branch atual.

### Branch
* Comando git branch - Lista todas as branchs.
 
* Comando git branch "nome_da_nova_branch" - Cria uma nova branch.

* Comando git checkout "nome_da_branch" - Aponta para qual branch vc quer trabalhar.

* Comando git merge "nome_da_branch" - Mescla as alterações feitas entre os branchs.

        Para realizar o merge, é necessário estar no branch que deverá receber as alterações. O merge pode automático ou manual. O merge automático será feito em arquivos textos que não sofreram alterações nas mesmas linhas, já o merge manual será feito em arquivos textos que sofreram alterações nas mesmas linhas.