# Curso-Git
Conceitos basicos e Comandos de Git


Curso voltado a comandos de gitHub 


# Inicando um Repositorio
  - git init
  
# Adicionando um novo arquivo
  - git add NOME DO ARQUIVO
  - git add . Adicionar todos os arquivos

# Removendo um arquivo local / Servidor
  - git -rm -f NOME DO ARQUIVO para remover de forma forçada os arquivos locais.
  - git - rm NOME DO ARQUIVO para remover apenas do add.
  
# Voltando ao estado anterior de forma local antes de Realizar o comando git add
  - git checkout -- NOME DO ARQUIVO

# Ligando o repositorio Local com o repositorio Remoto
  - git remote -v -> verifca se você ja tem um repositorio gravado na pasta.
  - git remote add origin URL
  - git push --set-upstream origin master / git push --set-upstream origin master -> Força o update
  - git push origin master --force

# Clonando um repositorio 
  - git clone URL

# Atualizando o repositorio local com o repositorio remoto
  - git pull
  
# Como verificar os log's dos commit
  - git log
  - :q para sair do log

# Como criar suas Tag's
  - git tag NOME/NUMERO
  - git push --tags

# Branch
  - criando uma branch -> git branch feature/NOME_DA_BRANCH
  - verificando em branch você está -> git branch
  - Deletar uma branch -> git branch -D feature/NOME_DA_BRANCH
  - mudar de branch -> git checkout feature/NOME_DA_BRANCH

# Merge
  - Em primeiro ligar você vai entrar na branch em que deseja realizar o merge ou a no meu caso especifico a branch master
  - git merge feature/NOME_DA_BRANCH
  - criando e mudando para uma nova branch via terminal -> git checkout -b feature/NOME_DA_BRANCH

