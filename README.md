# Comandos Básicos do Git
> Aqui estão alguns comandos básicos do Git que podem ser úteis ao trabalhar com repositórios Git. Certifique-se de ter o Git instalado no seu sistema antes de começar.

## Configuração Inicial

```bash
#Para criar um repositório Git, utilize o comando:
$ git init

```

## Trabalhando com Arquivos e Diretórios

```bash
#1.Verificar o Estado dos Arquivos/Diretórios, use:
$ git status

#2.Para adicionar um arquivo específico ao staging, utilize:
$ git add nome_do_arquivo

#3.Para adicionar todos os arquivos ao staging, use:
$ git add .

#4.Para fazer commit dos arquivos no staging, utilize:
$ git commit -m "Sua mensagem de commit"

#5.Para remover um arquivo do repositório, use:
$ git rm nome_do_arquivo

```
## Branches e Trabalho Remoto

```bash
#1.Para criar uma nova branch, use:
$ git branch nome-da-sua-nova-branch

#2.Para mudar automaticamente para uma nova branch, utilize:
$ git checkout -b nome-da-sua-nova-branch

#3.Para unir duas branches distintas, use:
$ git merge nome-da-outra-branch

#4.Para enviar suas alterações para o GitHub, utilize:
$ git push -u origin main

#5.Para sincronizar o repositório local com as mudanças do repositório remoto, utilize:
$ git pull

#6.Para clonar um repositório existente, use:
$ git clone URL_do_repositório

```
## Visualizando e Gerenciando Alterações

```bash
#1.Para acessar o histórico de alterações, utilize:
$ git log

#2.Para desfazer as alterações em um arquivo, use:
$ git checkout nome_do_arquivo

#3.Para resetar as mudanças para o estado da branch remota, utilize:
$ git reset --hard origin/main

#4.Para listar as branches disponíveis, use:
$ git branch

```
## Stash, Tags e Outros Comandos

```bash
#1.Para salvar as modificações atuais e trabalhar em outra tarefa, utilize:
$ git stash

#2.Para criar tags, use:
$ git tag -a nome_da_tag -m "Sua mensagem para a tag"

#3.Para verificar e limpar arquivos não rastreados, utilize:
$ git clean -n  # Verifica
$ git clean -f  # Limpa

#4.Outros Comandos Úteis :
Você também pode usar comandos como git diff, git remote, git submodule, entre outros, para tarefas específicas.
```


>Foi desenvolvido no curso de Git da  **[Udemy](https://www.udemy.com/course/git-e-github-do-basico-ao-avancado-c-gist-e-github-pages/)**

<p align="center"> Por ✨  by Alita Kallyne</p>
