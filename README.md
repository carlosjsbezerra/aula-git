# GIT GITHUB

Guia prático para iniciantes.

# Instalação

https://git-scm.com/downloads

# SCENES

- [x] Iniciar a linha do tempo / repositorio git
  * `git init`
- [x] Criar um pontos na história da produção do seu projeto.
  * `git commit -am "meu primeiro commit"`
- [x] Verificar mudanças feitas na história do projeto projeto.
  * `git log`
  * `status`
- [x] Reevizitar os pontos feitos
  * `git show 361b40d3c76a393ccf1064f1397d4031a7974970`
- [x] Você começa um nova funcionalidade no seu projeto, sem estragar o que já foi feito.
  * `git branch feature/cart ou git -b feature/cart`
- [x] mudar para o novo branch
  * `git checkout feature/cart`
- [x] voltar para a branch master
  * `git checkout master`
- [x] olhar toda a linha do tempo
  * `git branch`
- [x] Adicionar as novas funcionalidades ao seu projeto em produção.
- [x] adicionar as novas funcionalidas da branch feature/cart
	ao projeto master (unir linhas do tempo)
  * `git merge feature/cart`
- [x] Deletar o branch
  * `git branch -D feature/cart`
- [x] Listar os branch
  * `git branch` 
- [x] colocar o projeto na nuvem.
  * `git remote add origin https://github.com/carlosjulianodasilvabezerra/aula-git.git`
  * `git push -u origin master`
- [x] Ver os repositorios remotos
  * `git remote -v`
- [x] evitar que toda vez que for fazer push pedir as credencias.
  * `git config credential.helper store`
- [x] Fazer um puche na nuvem atualizando o repositório local
  * `git pull`
- [x] Você precisa voltar um arquivo para um determinado momento da linha do.
  * `git checkout bu23ujblk23203984bjoweroi23098432 -- package.json`
- [x] Recuperar algo deletado
  * `git checkout -- package.json`


* `git init` // inicia a linha do tempo
* `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
* `git commit` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo / commit
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // gerencia novas linhas do tempo
* `git checkout` // manipula as linhas do tempo
* `git merge` // unir linhas do tempo
* `git push` // envia alterações locais para o repositôrio remoto
* `git clone` // clonar um projeto / repositório
* `git pull` // puxar do repositório remoto atualizando o local