# Atividades sobre Git e GitHub

Este repositório contém atividades de prática sobre Git e GitHub

<img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/GitHub_Invertocat_Logo.svg" width="200" />

## Objetivo
Aprender a implementar as funcionalidades do Git e GitHub

## Dependências

* Instale o Git - [Git - Página Oficial](https://git-scm.com/)

 
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Git-logo.svg" width="300" />

 

## Como utilizar

###  1. Passos iniciais

* Crie um novo repositório no GitHub:

<img src="https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp" width="500" />

* Clique no repositório, vá em *code* e copie o link HTTPS

<img src="https://itknowledgeexchange.techtarget.com/coffee-talk/files/2020/11/find-github-url.png" width="500" />

* Na área de trabalho abra o git bash

<img src="https://help.lieberlieber.com/LemonTree/attachments/Verify%20Git%20LFS%20Setup/GitBashHere.png" width="300" />

* Digite no terminal:

```git
git clone `linkHTTPS`
```

* Você verá a pasta do repositório no seu computador, modifique, delete ou adicione arquivos à pasta

* Após todas as modificações clique com o botão direito na pasta e selecione `Open Git Bash here`

---

###  2. Comandos

* Crie uma branch secundária

```git
git branch new-1
```

* Mude a branch que você está, perceba que a branch atual é a `main`

```git
git checkout new-1
```

* Adicione os arquivos

```git
git add --all
```

* Verifique os arquivos

```git
git status
```

* Faça o `commit` dos arquivos

```git
git commit -m"comentário curto sobre as mudanças"
```

* Faça o upload dos arquivos

```git
git push origin new-1
```

* Mude para a branch `main`

```git
git checkout main
```

---

###  3. Pull Request

* Após todos esses passos você verá uma mensagem no seu repositório do GitHub

<img src="https://hisham.hm/img/posts/github-comparepr.png" width="500" />



* Você poderá rever os arquivos, aceitar o merge ou recusar, explore!
* Há outros comandos do git também que são interessantes mas esses são os principais



