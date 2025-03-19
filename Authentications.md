# Authentications

## Authentication types

### Via username and password

1. Adicionar username e password as configurações do Git.

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

2. Realizar login via browser

O login será solicitado automaticamente ao realizar push do local repository to remote repository.

### Via personal access token

1. Gerar o token na conta do GitHub

    Configurações >> Developer settings

2. Configurar Windows

    Remover credenciais se já existirem em: Painel de Controle >> Contas de usuário >> Gerenciados de Credenciais >> Credenciais do Windows

3. Acessar Git Bash e configurar username e userpassword

Use o "git config" para isso.