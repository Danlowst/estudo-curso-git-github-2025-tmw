# Curso TMW Git \& GitHub 2025

Aqui estão todos os arquivos que produzi durante o curso de Git \& GitHub do TeoMeWhy.

Englobando o básico de Git, GitHub, seus comandos e integração com a IDE Visual Studio Code.

Além disso, abordando como se organizar com conceitos de Git Flow, padronizações de branchs e commits, juntamente com resolução de conflitos.

## Fluxo de trabalho Git local

01. git checkout -b <nova_branch>
02. cria ou atualiza arquivos
03. git status
04. git add *arquivos*
05. git status
06. git commit -m "minha mensagem"
07. git checkout main
08. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

01. git clone
02. git checkout -b <nova_branch> 
03. alterações de arquivos
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

01. Fork do projeto para seu próprio GitHub
02. git clone <endereço do projeto fork>
03. git checkout -b <nova_branch>
04. alterações de arquivos 
05. git status
06. git add *arquivos*
07. git status
08. git commit -m "nova mensagem"
09. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>