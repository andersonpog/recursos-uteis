## 

## Iniciando o repositório

### Criando um repositório local

git init 

git remote add origin \<endereço_do_repositório\>

### Importando o repositório

git clone \<endereço_do_repositório\>



## Configurações importantes

 git config --global user.email \<email\> (remover flag global para salvar apenas no diretório)

git config --global user.name \<nome\> (remover flag global para salvar apenas no diretório)



## Salvando as modificações

#### Adicionando ao stage

git add \<arquivos\>
git add \* (Adiciona todos os arquivos do diretório)

#### Preparando o commit

git commit -m "Messagem informativa"

#### Enviando  arquivos

git push origin main

git push \<local\> \<branch\>



## Comandos úteis

git status (Exibe ciclo de vida dos arquivos)

git remote -v (Exibe repositório conectado)