# GIT E GITHUB

Guia prático para iniciantes.

### INSTALL

https://git-scm.com/download

# BASIC COMMANDS

- git init
- git add (. -> to add all)
- git push
- git pull
- git status
- git log
- git show (?id -> to see only one log)
- git branch (create a branch)
- git checkout (-b -> create branch and check in)
- git checkout (id -> log) -- file (to restore any file that you want)
- git checkout -- file (restore deleted file **before commit**)
- git merge (branch)
- git branch -D (branch name)
- git remote add origin (url -> to add the url for your .git)

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto.
- [x] Você deseja verificar mudanças feitas no seu projeto.
- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção.
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.
- [x] Você quer por seu projeto na nuvem.
- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time.
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.
- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recuperar algo deletado.

`git init` // inicia a linha do tempo
`git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
`git commit` // adiciona um ponto na linha do tempo
`git log` // visualiza os pontos na linha do tempo / commit
`git status` // informa o estado das alterações do nosso projeto
`git show` // apresenta determinado ponto na história
`git branch` // gerenciar novas linhas do tempo
`git checkout` // manipula as linhas do tempo
`git merge` // unir linhas do tempo
`git push` // envia alterações locais para o repositório remoto
`git clone` // clonar um projeto / repositório
`git pull` // puxa do repositório remoto
