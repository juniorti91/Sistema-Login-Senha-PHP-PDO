# Sistema-Login-Senha-PDO
Desenvolvimento de um sistema de login e senha com PDO

![image](https://user-images.githubusercontent.com/14321414/131234488-af45aaad-fc3e-4992-8ac5-537a805a8f34.png)


# Sistema de Login e Senha com PHP e PDO

Este repositório contém a implementação de um sistema de login e senha utilizando PHP com PDO (PHP Data Objects) para interação segura com o banco de dados MySQL. O sistema permite o registro de usuários, autenticação, gerenciamento de sessões e redefinição de senha.

## Tecnologias Utilizadas

- **Backend**: PHP
- **Banco de Dados**: MySQL
- **Segurança**: PDO para prevenção contra SQL Injection, `password_hash()` e `password_verify()` para armazenamento seguro de senhas

## Estrutura do Repositório

A estrutura do repositório é organizada da seguinte forma:

- **css/**: Arquivos de estilo CSS para a interface.
- **img/**: Imagens utilizadas na interface.
- **Usuario.class.php**: Classe PHP para gerenciamento de usuários.
- **conexao1.php** e **conexao2.php**: Arquivos de configuração para conexão com o banco de dados.
- **index2.php**: Página inicial do sistema.
- **logar.php**: Script para autenticação de usuários.
- **login.php**: Página de login.
- **README.md**: Documentação do projeto.

## Funcionalidades

- **Cadastro de Usuário**: Permite que novos usuários se registrem no sistema.
- **Login de Usuário**: Autentica usuários com nome de usuário e senha.
- **Gerenciamento de Sessões**: Mantém o estado de login do usuário durante a navegação.
- **Redefinição de Senha**: Permite que usuários redefinam suas senhas de forma segura.

## Como Executar o Projeto

### Pré-requisitos

- Servidor web com suporte a PHP (por exemplo, XAMPP, WAMP, ou servidor Linux com Apache/Nginx).
- Banco de dados MySQL.
- Editor de código (por exemplo, Visual Studio Code, Sublime Text).

### Passos para Execução

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/juniorti91/Sistema-Login-Senha-PHP-PDO.git
