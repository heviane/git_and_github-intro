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

2. Windows

    Remover credenciais antigas em: 
    Painel de Controle >> Contas de usuário >> Gerenciados de Credenciais >> Credenciais do Windows

3. Configurar username e userpassword

Use o "git config" via Git Bash para isso.
Essa configuração será necessária para a realização de commits.

4. Adicionar token

Ao fazer o primeiro commit ou clonar um repositório vai abrir um popup.
Selecione a autenticação via Token e informe o token.