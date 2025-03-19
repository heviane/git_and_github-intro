# Git Bash: "git config" command

O comando `git config` é usado para definir ou visualizar configurações do Git, como nome de usuário, e-mail, alias de comandos e preferências globais.  

As configurações podem ser **locais** (repositório atual), **globais** (usuário) ou **de sistema**.

## Visualizar todas as configurações:

```bash
git config --list
```

## Exemplos:

- **Configuração global do usuário:**

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

- **Definir um editor padrão:**  

```bash
git config --global core.editor "code --wait"
```

- **Criar um alias (atalho) para um comando:** 

```bash
git config --global alias.st "status"
```
