# Variações do Girt Reset

## Observações:

#### 1° O recomendado é digitar os comandos listados no Git Bash;

#### 2° Os nomes que estão entre aspas simples (' ') simbolizam os termos a serem escolhidos pelo programador;

#### 3° Quando houver aspas duplas (" "), deve-se escrevê-las no código também;

#### 4° Casos em que há aspas simples e aspas duplas juntas significa que o termo escolhido pelo programador deve estar entre aspas duplas, no código.

#### + O commit atual é deletado e vira o indicado, e os arquivos do commit deletado são colocados em Staged (voltam ao estágio antes do commit):
```
git reset --soft 'codigoCommit'

```
##

#### + O commit atual é deletado e vira o indicado, e os arquivos do commit deletado são colocados em Untracked (voltam ao estágio antes do add):
```
git reset --mixed 'codigoCommit'

```
##

#### + O commit atual é deletado e vira o indicado, além disso os arquivos do commit deletado são deletados também (literalmente vira o commit indicado pelo código, 
e apaga qualquer traço do commit resetado):
```
git reset --hard codigoCommit

```
##
