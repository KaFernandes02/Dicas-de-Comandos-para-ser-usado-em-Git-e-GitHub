# Revisão de Comando para Git e GitHub

Alguns comandos para facilitar o uso do git e github para iniciantes. (Como eu)

## 🔍 Criação de repósitorios em Local
- mkdir (Nome da Pasta): Cria uma nova pasta no computador

- cd (Nome da Pasta): Entra na pasta criada

- git init: Faz a pasta ser um diretorio git

- cd .git: Entra no diretorio Git Git

- cd ..: Retorna para a pasta anterior.

- Touch: Cria um novo arquivo na pasta.

- cat config: Fornece as informações daquela pasta.

## Pegar um repositorio remoto para um local:
- git clone (URL): Copia o repositorio para o local

- git remote add origins URL: Copia o repositorio local para o remoto

- touch (Nome da pasta)/Nome do arquivo: Cria um arquivo ou pasta dentro de outro arquivo.

## Alterações nos repositorios e salvamentos
- git log: Historico de Alterações

- echo /(nome da pasta)> gitignore.: Cria uma pasta para o git ignorar as alterações

- echo > .gitignore: retira as coisas da pasta

- git add: adiciona os arquivos para a zona de preparamento

- git commit -m"": Salva as alterações

- git status: Mostra os status das alterações

## Desfazendo Alterações:
- GIt restore (Nome do arquivo)

- git commit -ammend -m"":Altera a ultima mesagem dada no commit

- git reset --soft (Dados do commit): Desfaz o utlimo commit, retornando os arquivos para a fase de preparação

- git reset (Dados do commit): desfaz o commit e retorna os arquivos para a area de modificação do git, antes da area de prepareção

- git reset --hard (dados do commit): desfaz completamento o commit e apaga os arquivos

## Enviando e baixando as alterações para o repositorio remoto
- Para linkar o diretorio: git remote add origins URL

- Para enviar o diretorio: git push -u origins main

- para puxar da linha de comando do diretorio remoto: git pull

## Branches (Ramos)
- Para criar uma nova branch em cima do commit: git checkout -b (Nome da Brench)

- Criar um arquivo de texto: echo "(Conteudo do arquivo)" > (Nome do arquivo)

- Para voltar a brench principal: git checkout main / main = nome do branch principal

- Para ver os ultimos commit de cada branch: git branch -v

- git branch: resulta nas branch criadas

- git branch -d (nome da branch): exclui a branch
