# Authentications Types

## Username and Password

1. Adicionar username e password as configurações do Git.

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

2. Realizar login via browser

Ao fazer commit/push ou clonar um repositório vai abrir um popup.
Selecione a autenticação via Browser e informe o username e password.

## Personal Access Token

1. Gerar o token na conta do GitHub

    Configurações >> Developer settings

2. Windows

    Remover credenciais antigas em: 
    Painel de Controle >> Contas de usuário >> Gerenciados de Credenciais >> Credenciais do Windows

3. Configurar username e userpassword

Use o "git config" via Git Bash para isso.
Essa configuração será necessária para a realização de commits.

4. Adicionar token

Ao fazer commit/push ou clonar um repositório vai abrir um popup.
Selecione a autenticação via Token e informe o token.

## SSH Key

## Two-Factor Authentication - 2FA

