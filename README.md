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
  - git remote add origin URL
  - git push --set-upstream origin master
