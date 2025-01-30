# Curso TMW Git & GitHub 2025

Curso para aprender a trabalhar com versionamento de código e repositórios remotos com GitHub, Git Flow e Visual Studio Code.


Confira tudo no YouTube, é grátis! Segue o link:

[Curso Git 2025] (https://youtube.com/)

Acompanhe nossas redes socias e tudo o que está por vir no nosso 2025.

Vai ser muito legal ter você por perto.

## Fluxo de trabalho Git local

1. git checkout -b <nova branch>
2. cria ou atualiza arquivos
3. git status
4. git add "arquivos"
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto prórpio ou da sua empresa).

1. git clone <endereco do projeto>
2. git checkout -b <nova_branch>
3. alteracoes de arquivos
4. git status
5. git add "arquivos"
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abrir pull request no GitHub para main
10. excluir nova branch na origin
11. git checkout main
12. git branch -d <nova_branch>

## Fluxo de trabalho GitHub <> Local (projeto open-source).

1. Fork do projeto para seu próprio GitHub
2. git clone <endereco do projeto fork>
3. git checkout -b <nova_branch>
4. alteracoes de arquivos
5. git status
6. git add "arquivos"
7. git status
8. git commit -m "nova mensagem"
10. abrir pull request no GitHub da branch fork para a main do projeto original
11. excluir nova branch na origin
12. git checkout main
13. git branch -d <nova_branch>
-----

Pessoas participantes:


Gabriel Bertolini