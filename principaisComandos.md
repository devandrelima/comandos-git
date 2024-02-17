# Comandos principais do Git

## Observações:

#### 1° O recomendado é digitar os comandos listados no Git Bash;

#### 2° Os nomes que estão entre aspas simples (' ') simbolizam os termos a serem escolhidos pelo programador;

#### 3° Quando houver aspas duplas (" "), deve-se escrevê-las no código também;

#### 4° Casos em que há aspas simples e aspas duplas juntas significa que o termo escolhido pelo programador deve estar entre aspas duplas, no código.

## Comandos Básicos:

#### - Inicializa o git na pasta desejada:
```
git init

```
##

#### - Configura o git para sempre iniciar o repositório com o branch main como padrão: 
```
git config --global init.defaultBranch main 

```
#### Mais comandos para configurar o git: [Variações do git config]() 
##

#### - Prepara todos os arquivos para criar um commit: 
```
git add . 

```
##### ou
```
git add *

```
##

#### - Cria um commit: 
```
git commit -m "'nomeCommit'" 

```
##

#### - Diz se o seu código precisa ser adicionado, commitado ou se está limpo: 
```
git status 

```
##

####  - Conecta o seu repositório normal com o gitHub(repositório remoto):

```
git remote add origin 'linkRepositorioGithub'

```
##

#### - Envia o commit do repositório local para o repositório remoto: 
```
git push origin main

```
##

#### - Trás o commit do repositório remoto para o repositório local: 
```
git pull origin main

```
##

#### - Mostra histórico de commits do repositório local: 
```
git log

```
##
#### - Os arquivos do commit resetado voltam ao estágio antes do git add e o commit atual torna-se o indicado pelo código: 
```
git reset 'codigoCommit' 

```
#### Mais comandos para resetar o commit: [Variações do git reset]() 
##
#### - Cria um novo commit baseado no que você indica com o código, retirando todas as mudanças que há no commit mais atual: 
```
git revert 'codigoCommit'

```
##
#### - Criar uma nova branch: 
```
git checkout -b 'nomeNovaBranch'

```
##
#### - Alterna da branch atual para a indicada: 
```
git checkout 'nomeBranch'

```
##
#### - Mescla a branch escolhida com a que o programador está atualmente: 
```
git merge 'nomeBranch'

```
##