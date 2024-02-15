# Comandos principais do Git

## Observações:

#### 1° O recomendado é digitar os comandos listados no Git Bash;

#### 2° A quantidade de sinais de ‘+’ após um comando corresponde ao número de variações listadas em um arquivo separado para detalhar o mesmo; 

#### 3° Os nomes que estão entre aspas simples (' ') simbolizam os termos a serem escolhidos pelo programador;

#### 4° Quando houver aspas duplas (" "), deve-se escrevê-las no código também;

#### 5° Casos em que há aspas simples e aspas duplas juntas significa que o termo escolhido pelo programador deve estar entre aspas duplas, no código.

## Comandos Básicos:

#### - Inicializa o git na pasta desejada:
```
git init

```
#### - Configura o git de forma global ([Variações]()): 
```
git config --global +++++++ 

```
#### - Prepara arquivos para criar um commit ([Variações]()): 
```
git add +++ 

```
#### - Cria um commit: 
```
git commit -m "'nomeCommit'" 

```
#### - Diz se o seu código precisa ser adicionado, commitado ou se está limpo: 
```
git status 

```
#### - Trata a conexão com o repositório remoto ([Variações]()): 
```
git remote ++

```
#### - Envia o commit do repositório local para o repositório remoto: 
```
git push origin main

```
#### - Trás o commit do repositório remoto para o repositório local: 
```
git pull origin main

```