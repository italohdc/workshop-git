# Passo 2 - Instalação e Configuração (Windows)

Siga os seguinte passos para instalar o Git Bash no seu computador:

1. Baixe a última versão do ([Instalador do Git para Windows](https://git-scm.com/download/win)).

2. Após iniciar o instalador, você deverá ver o assistente de instalação do Git. Avance os passos até finalizar a instalação. As opções padrões de instalação são suficientes para realizar este workshop.

![Imagem de exemplo da interface do instalador](/Assets/02/windows_install_window.png)

3. Abra o terminal **Git Bash**.

![Exemplo de janela do Git Bash](/Assets/02/windows_git_bash.png)

4. É necessário cofigurar o seu usuário e email no Git. Para isso, execute os seguinte comandos no terminal (uma linha por vez), substituindo **"SEU NOME"** pelo seu **nome** e **"USER@EMAIL.COM"** pelo **email** que você utilizou para criar a sua conta do GitHub:

```
git config --global user.name "SEU NOME"
```

```
git config --global user.email "USER@EMAIL.COM"
```

---

Este guia de instalação do Git para Windows foi baseado no [tutorial de instalação do Git feito pela Atlassian](https://www.atlassian.com/git/tutorials/install-git#windows) (em inglês).
