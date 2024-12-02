# AppLogin

O **AppLogin** é um aplicativo Android que implementa um sistema básico de autenticação. Ele permite que os usuários se registrem, façam login e visualizem suas informações básicas na tela principal. As credenciais são armazenadas localmente utilizando o `SharedPreferences`.

---

## Funcionalidades

- **Registro de Usuários**:
  - Inscrição com nome, e-mail e senha.
  - Armazenamento seguro das credenciais utilizando `SharedPreferences`.

- **Login de Usuários**:
  - Verificação de e-mail e senha.
  - Redirecionamento para a tela principal em caso de sucesso.

- **Tela Principal**:
  - Exibição do nome e e-mail do usuário.
  - Botão para logout, redirecionando para a tela de login.

---

## Requisitos

- Android Studio (versão 2022.1.1 ou superior).
- Android SDK versão mínima: 24 (Android 7.0).

---

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/applogin.git
