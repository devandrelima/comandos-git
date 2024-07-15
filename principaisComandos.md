# Comandos principais do Git

## Observações:

#### 1° O recomendado é digitar os comandos listados no Git Bash;

#### 2° Os nomes que estão entre aspas simples (' ') simbolizam os termos a serem escolhidos pelo programador;

#### 3° Quando houver aspas duplas (" "), deve-se escrevê-las no código também;

#### 4° Casos em que há aspas simples e aspas duplas juntas significa que o termo escolhido pelo programador deve estar entre aspas duplas, no código.

## Comandos Básicos:

#### + Inicializa o git na pasta desejada:
```
git init

```
##

#### + Configura o git para sempre iniciar o repositório com o branch main como padrão: 
```
git config --global init.defaultBranch main 

```
#### Mais comandos para configurar o git: [Variações do git config](https://github.com/devandrelima/comandos-git/blob/main/varGitConfig.md) 
##

#### + Prepara todos os arquivos para criar um commit: 
```
git add . 

```
##### ou
```
git add *

```
##

#### + Cria um commit: 
```
git commit -m " 'nomeCommit' " 

```
##

#### + Diz se o seu código precisa ser adicionado, commitado ou se está limpo: 
```
git status 

```
##

####  + Diz se estou conectado com algum repositorio remoto, e com qual estou ligado:

```
git remote -v

```
##

####  + Conecta o seu repositório normal com o gitHub(repositório remoto):

```
git remote add origin 'linkRepositorioGithub'

```
##

#### + Envia o commit do repositório local para o repositório remoto: 
```
git push origin main

```
##

#### + Trás o commit do repositório remoto para o repositório local: 
```
git pull origin main

```
##

#### + Se o git pull comum não funcionar, esse indicado abaixo provavelmente resolverá seu problema: 
```
git pull origin main --allow-unrelated-histories

```
##### Após inserir o comando, segure em ‘Ctrl w q’ para o git funcionar normalmente.
##

#### + Mostra histórico de commits do repositório local: 
```
git log

```
##
#### + Os arquivos do commit resetado voltam ao estágio antes do git add e o commit atual torna-se o indicado pelo código: 
```
git reset 'codigoCommit' 

```
#### Mais comandos para resetar o commit: [Variações do git reset](https://github.com/devandrelima/comandos-git/blob/main/varGitReset.md) 
##
#### + Cria um novo commit baseado no que você indica com o código, retirando todas as mudanças que há no commit mais atual: 
```
git revert 'codigoCommit'

```
##
#### + Criar uma nova branch: 
```
git checkout -b 'nomeNovaBranch'

```
##
#### + Alterna da branch atual para a indicada: 
```
git checkout 'nomeBranch'

```
##
#### + Mostra as branchs que existem e a que estamos inseridos: 
```
git branch

```
#### Mais comandos relacionados as brachs: [Variações do git branch](https://github.com/devandrelima/comandos-git/blob/main/varGitBranch.md) 
##
#### + Mescla a branch escolhida com a que o programador está atualmente: 
```
git merge 'nomeBranch'

```
##
#### + Baixa as alterações do repositório remoto, mas sem mesclar com a branch local: 
```
git fetch origin main

```
##
#### + Mostra as diferenças entre o commit remoto e o commit local: 
```
git diff 'nomeCommit'

```
##
