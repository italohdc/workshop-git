# 💾 Passo 2 - Instalação e Configuração (Linux)

## Ubuntu / Debian

Siga os seguinte passos para instalar o Git no seu computador:

1. Abra o seu terminal e execute os seguinte comandos. Eles irão instalar o Git utilizando o gerenciador de pacotes padrão do Ubuntu/Debian.

```
sudo apt update
sudo apt install git
```

5. É necessário cofigurar o seu usuário e email no Git. Para isso, execute os seguinte comandos no terminal, substituindo **"SEU NOME"** pelo seu **nome** e **"USER@EMAIL.COM"** pelo **email** que você utilizou para criar a sua conta do GitHub:

```
git config --global user.name "SEU NOME"
git config --global user.email "USER@EMAIL.COM"
```

---

Este guia de instalação do Git para macOS foi baseado no [tutorial de instalação do Git feito pela Atlassian](https://www.atlassian.com/git/tutorials/install-git#linux) (em inglês).