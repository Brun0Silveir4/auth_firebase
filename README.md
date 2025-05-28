# Projeto Kotlin - Login com Firebase Authentication


Este projeto é um aplicativo desenvolvido em **Kotlin** que implementa o sistema de login utilizando o **Firebase Authentication**. Permite autenticação de usuários por email e senha, integrando com o backend do Firebase para gerenciamento seguro das credenciais.

<br>

## ⚙️ Tecnologias Utilizadas

- Kotlin para desenvolvimento Android
- Firebase Authentication para autenticação de usuários
- Firebase SDK para integração com serviços do Firebase
- Android Studio como IDE principal

<br>

## 🧩 Funcionalidades

- Cadastro de novos usuários com email e senha
- Login de usuários existentes
- Recuperação de senha via email
- Gerenciamento de sessão do usuário no app
- Integração segura com Firebase Authentication
<br>

## 🚀 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/Brun0Silveir4/auth_firebase
```

### 2. Acesse dentro da sua IDE (preferência android studio)

### 3. Configure o Firebase
* Crie um projeto no firebase console
* Adicione o seu app android com o package name correto
* Baixe o arquivo `google-services.json` e coloque na pasta `app/` do projeto

### 4. Configure as dependências no Gradle
Certifique-se que o `build.gradle` do projeto contenha as dependências do Firebase Authentication e o plugin do Google Services, por exemplo:
```java
    implementation(platform(libs.firebase.bom))
    implementation(libs.firebase.ui.auth)
    implementation(libs.firebase.auth)
    implementation("androidx.navigation:navigation-compose:2.7.3")
    implementation(libs.firebase.firestore)
```

### 5. Rode a aplicação
Abra o projeto no Android Studio e execute em um emulador ou dispositivo real.

<br>

## 🙋‍♂️ Autor

Desenvolvido por Bruno Silveira. Contato:  
• [LinkedIn](https://www.linkedin.com/in/bruno-silveira-dionisio/)  
• [GitHub](https://github.com/Brun0Silveir4)  
• bruno.silveira.dionisio@gmail.com