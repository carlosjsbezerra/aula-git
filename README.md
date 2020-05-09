<h1 align="center">
    <img alt="git" src="https://img.youtube.com/vi/2alg7MQ6_sI/maxresdefault.jpg" width="600px" />
</h1>

# GIT GITHUB

Guia prático para iniciantes.

# Instalação

https://git-scm.com/downloads

# SCENES

## 1. Iniciar a linha do tempo / repositorio git
* `git init`

## 2. Criar um pontos na história da produção do seu projeto.
* `git commit -am "meu primeiro commit"`

## 3. Verificar mudanças feitas na história do projeto projeto.
* `git log`
* `status`

## 4. Reevizitar os pontos feitos
* `git show 361b40d3c76a393ccf1064f1397d4031a7974970`

## 5. Você começa um nova funcionalidade no seu projeto, sem estragar o que já foi feito.
* `git branch feature/cart ou git -b feature/cart`

## 6. mudar para o novo branch
* `git checkout feature/cart`

## 7. voltar para a branch master
* `git checkout master`

## 8. olhar toda a linha do tempo
* `git branch`

## 9. adicionar as novas funcionalidas da branch feature/cart
ao projeto master (unir linhas do tempo)
* `git merge feature/cart`

## 10. Deletar o branch
* `git branch -D feature/cart`

## 11. Listar os branch
* `git branch` 

## 12. colocar o projeto na nuvem.
* `git remote add origin https://github.com/carlosjulianodasilvabezerra/aula-git.git`
* `git push -u origin master`

## 13. Ver os repositorios remotos
* `git remote -v`

## 14. evitar que toda vez que for fazer push pedir as credencias.
* `git config credential.helper store`

## 15. Fazer um puche na nuvem atualizando o repositório local
* `git pull`

## 16. Você precisa voltar um arquivo para um determinado momento da linha do.
* `git checkout bu23ujblk23203984bjoweroi23098432 -- package.json`

## 17. Recuperar algo deletado
* `git checkout -- package.json`

## CONTRIBUIR EM UM PROJETO REMOTE
#### 1. Clonar o repositorio remote
> git clone https://github.com/carlosjulianodasilvabezerra/8-ways-looping-arrays-javascript.git
> git remote -v

#### 2. Atualizando o fork
> git remote add upstream https://github.com/gabrielfroes/8-ways-looping-arrays-javascript
> git fetch upstream
> git merge upstream/master
> git push

#### 3. Criar um novo branch
> git checkout -b feature
> git add .
> git commit -m "lea-me"
> git push origin feature
