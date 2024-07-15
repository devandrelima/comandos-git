# Variações do Git config

## Observações:

#### 1° O recomendado é digitar os comandos listados no Git Bash;

#### 2° Os nomes que estão entre aspas simples (' ') simbolizam os termos a serem escolhidos pelo programador;

#### 3° Quando houver aspas duplas (" "), deve-se escrevê-las no código também;

#### 4° Casos em que há aspas simples e aspas duplas juntas significa que o termo escolhido pelo programador deve estar entre aspas duplas, no código.

#### + Dá um apelido para o comando do git que você quiser:
```
git config --global alias.'nomeApelido' 'nomeCodigoQueDesejaMudar'

```
##

#### + Retira o apelido que você deu para o comando:
```
git config --global –unset alias.'nomeApelido'

```
##

#### + Vincula um email ao git:
```
git config --global user.email “ 'seuEmail' ”

```
##

#### + Apaga o email vinculado ao git:
```
git config --global --unset user.email

```
##

#### + Vincula um nome de usuário ao git:
```
git config --global user.name “ 'nomeUsuario' ”

```
##

#### + Apaga o nome de usuário vinculado ao git:
```
git config --global --unset user.name

```
##
