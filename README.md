# Aula sobre Git :: Code.Education


## Criando um Repositório Git


Para criar um **repositório Git** no diretório atual, execute o comando `git init`.

O sistema git irá criar um diretório oculto chamado `.git` com toda a estrutura do repositório criado.

A partir desse ponto, o repositório já está disponível para controlar as versões dos arquivos e diretórios do projeto.


## Configuração inicial do repositório


Ao criar um repositório git, devemos definir as informações básicas do autor do projeto no repositório com os seguintes comandos:

```
git config --global user.name "Nome do Autor do Projeto"
git config --global user.email "email do autor"
```

## Exibindo o status dos arquivos


Para verificar o status de cada arquivo do repositório, execute o comando `git status`.


## Adicionando arquivos ao controle de versão


Para adicionar um ou mais arquivos ao controle de versão no repositório git, execute o comando `git add nome_do_arquivo`. Caso deseje adicionar todos os arquivos de uma única vez, use `git add .`.


## Efetuando o commit


Para confirmar a inclusão dos arquivos no controle de versão, execute o comando `git commit -m "descricao do commit"`.


## Efetuando push do repositório para o servidor remoto GitHub


O repositório já encontra-se com o controle de versão implementado. Para envia-lo para o GitHub, deve-se inicialmente criar um novo repositório no GitHub e seguir os passos exemplificados abaixo (como exemplo considere o repositório "aulagit"):

```
git remote add origin https://github.com/sua_conta/aulagit.git
git push origin master
```