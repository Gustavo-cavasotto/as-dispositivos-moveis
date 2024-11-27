# Flutter Authentication App

## 📝 Descrição
Um aplicativo Flutter com autenticação via **Firebase**, que permite:
- Fazer login.
- Registrar novos usuários.
- Redefinir senha.
- Logout.

A interface é intuitiva e inclui uma **Home Page** que consome uma API após o login bem-sucedido.

---

## 🚀 Funcionalidades
- **Login de Usuário:** Autenticação utilizando email e senha.
- **Cadastro de Usuário:** Registro de novos usuários no sistema.
- **Redefinição de Senha:** Função para recuperação de senha.
- **Home Page:** Tela inicial que consome uma API para exibir informações.

---

## 🛠️ Tecnologias Utilizadas
- **Flutter**: Framework para desenvolvimento mobile multiplataforma.
- **Firebase Authentication**: Serviço de autenticação para login, cadastro e recuperação de senhas.
- **Dart**: Linguagem de programação utilizada no Flutter.

---

## 📋 Pré-requisitos
- [Flutter](https://docs.flutter.dev/get-started/install)
- [Firebase CLI](https://firebase.google.com/docs/cli)
- Editor de código como [Visual Studio Code] [Android Studio].

## 🛠️ Configuração e Execução do Projeto

Siga as etapas abaixo para configurar e executar o projeto no seu ambiente local.

### **1. Instale o Flutter**
Certifique-se de que o Flutter esteja instalado no seu sistema. Se ainda não instalou:

Após a instalação, verifique se está tudo configurado corretamente:
cmd: ```flutter doctor```

### **2. Configure o Firebase
    2.1 Acesse o Firebase Console.
    2.2 Crie um novo projeto no Firebase.
    2.3 Habilite o Firebase Authentication no painel de autenticação.
    2.4 Baixe os arquivos de configuração:
    2.5 Android: Adicione o google-services.json ao diretório android/app.
    2.6 iOS: Adicione o GoogleService-Info.plist ao diretório ios/Runner.

### **3. Execute o Projeto
3.1 ```flutter run```
3.2 ```flutter pub get```