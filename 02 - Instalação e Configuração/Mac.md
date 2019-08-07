# Passo 2 - Instalação e Configuração (macOS)

Siga os seguinte passos para instalar o Git no seu computador:

1. Baixe a última versão do ([Instalador do Git para Mac](https://git-scm.com/download/mac)).

2. Abra o arquivo baixado e execute o instalador (caso apareça uma mensagem de segurança e não seja possível executar o arquivo, selecione-o com o botão direito e clique na opção "Abrir" e, na janela de confirmação, selecione "Abrir").

![Janela de arquivos existentes dentro do instalador e arquivo a ser aberto selecionado](/Assets/02/mac_folder.png)

3. Após iniciar o instalador, siga os passos até finalizar a instalação.

![Janela do assistente de instalação do Git](/Assets/02/mac_installer.png)

4. Abra uma instância do terminal.

![Instância do terminal do Mac aberta](/Assets/02/mac_terminal.png)

5. É necessário cofigurar o seu usuário e email no Git. Para isso, execute os seguinte comandos no terminal (uma linha por vez), substituindo **"SEU NOME"** pelo seu **nome** e **"USER@EMAIL.COM"** pelo **email** que você utilizou para criar a sua conta do GitHub:

```
git config --global user.name "SEU NOME"
```

```
git config --global user.email "USER@EMAIL.COM"
```

---

Este guia de instalação do Git para macOS foi baseado no [tutorial de instalação do Git feito pela Atlassian](https://www.atlassian.com/git/tutorials/install-git#mac-os-x) (em inglês).
