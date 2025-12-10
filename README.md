# 🎁 GiftNow

> **O Ifood dos Presentes**

O **GiftNow** é um aplicativo mobile focado na experiência de envio de presentes. Com uma interface moderna e intuitiva, o projeto visa conectar usuários a diversas lojas para enviar presentes com praticidade.

---

## 🗺️ Fluxo da Aplicação

Atualmente, o projeto possui o seguinte fluxo de navegação implementado:

### 1. 🔐 Autenticação 
A porta de entrada do aplicativo.
* **Login:** Acesso para usuários cadastrados.
* **Cadastro:** Registro de novos usuários.
* *Ação:* Ao logar ou cadastrar com sucesso, o usuário é direcionado para a **Home**.

### 2. 📱 Navegação Principal 
Após o login, o usuário tem acesso a 3 abas principais:

#### 🏠 Home 
A vitrine do aplicativo, onde são apresentados:
* **Lojas:** Listagem dos estabelecimentos parceiros.
* **Notas:** Avaliações e destaques.
* **Categorias:** Filtros para navegar por tipos de presentes.

#### 💳 Pagamentos (Carteira)
Tela dedicada ao gerenciamento financeiro do usuário:
* **Adicionar Cartão:** Formulário para inclusão de novos métodos de pagamento.
* **Gerenciar:** Visualização e remoção de cartões salvos.

#### 👤 Usuário (Perfil)
Área pessoal contendo:
* **Dados da Conta:** Exibição das informações do usuário logado.

---

## 🛠 Tecnologias utilizadas

* [React Native](https://reactnative.dev/)
* [Expo](https://expo.dev/)
* [React Navigation](https://reactnavigation.org/) (Stack & Bottom Tabs)
* Context API / Hooks (Gerenciamento de Estado)

---

## 🚀 Como rodar o projeto

### Pré-requisitos
* Node.js (LTS)
* npm ou yarn
* App **Expo Go** instalado no celular (ou emulador configurado).

### Passo a passo

1.  **Clone o repositório**
    ```bash
    git clone [https://github.com/seu-usuario/GiftNow.git](https://github.com/seu-usuario/GiftNow.git)
    cd GiftNow
    ```

2.  **Instale as dependências**
    ```bash
    npm install
    # ou
    yarn
    ```

3.  **Execute o projeto**
    ```bash
    npx expo start
    ```

4.  **Teste**
    * Leia o QR Code exibido no terminal com o app **Expo Go** (Android/iOS).

---

## 📂 Estrutura de Pastas

```text
├── .expo/
├── assets/               
├── src/
│   ├── components/       
│   ├── navigation/      
│   ├── screens/         
│   └── services/        
├── .gitignore
├── App.js                
├── app.json              
├── expo_output.log
├── index.js              
├── package-lock.json
├── package.json          
└── README.md             # Documentação do projeto
├── navigation/   # Configuração de rotas (AuthStack, AppTabs)
└── services/     # Lógica de API e dados
