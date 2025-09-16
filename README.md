*Read this in other languages: [English](#english-version).*
<br>

# Gestão de Usuários com Flask

## 📝 Sobre o Projeto

Este é um projeto simples de gestão de usuários (CRUD - Create, Read, Update, Delete) desenvolvido como parte dos estudos do microframework **Flask** em Python. O projeto foi desenvolvido com base em um tutorial do canal **Programador Python** no YouTube. O objetivo principal é aplicar conceitos fundamentais de desenvolvimento web, como rotas, templates e manipulação de requisições.

## Funcionalidades

-   **Listar usuários**: Visualização de todos os usuários cadastrados.
-   **Cadastrar usuário**: Adicionar um novo usuário à lista.
-   **Editar usuário**: Atualizar as informações de um usuário existente.
-   **Deletar usuário**: Remover um usuário da lista.
-   **Visualizar detalhes**: Exibir informações de um usuário específico em um modal.

## 💻 Tecnologias Utilizadas

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

-   **Backend**:
    -   **Python** e **Flask** para a construção das rotas e da lógica da aplicação.

-   **Frontend**:
    -   **HTML5** com **Jinja2** para a estruturação das páginas e renderização de dados.
    -   **CSS3** e **Bootstrap** para a estilização e responsividade da interface.
    -   **JavaScript (cru.js)**: As interações dinâmicas do frontend (como adicionar, editar e deletar sem recarregar a página) são gerenciadas pela biblioteca `cru.js`. Ela facilita a criação de requisições AJAX de forma declarativa, diretamente no HTML. Para mais informações, acesse o repositório oficial: [cru.js no GitHub](https://github.com/Iazzetta/cru.js).

## 🗃️ Banco de Dados

Por ser um projeto focado no aprendizado do Flask, **não utilizei um banco de dados persistente**. Os dados são armazenados em uma lista na memória da aplicação enquanto ela está em execução. Futuramente, pretendo implementar a integração com um banco de dados como SQLite ou PostgreSQL.

## Como Executar

Siga os passos abaixo para rodar o projeto em sua máquina local.

### Pré-requisitos

-   Python 3.x
-   pip (gerenciador de pacotes do Python)

### Instalação

1.  Clone o repositório:
    ```sh
    git clone https://github.com/lucascarvalho1808/gestao_usuarios_flask.git
    ```
2.  Navegue até o diretório do projeto:
    ```sh
    cd gestao_usuarios
    ```
3.  Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

### Executando a Aplicação

Para iniciar o servidor Flask, execute o comando:

```sh
python main.py
```

A aplicação estará disponível em `http://127.0.0.1:5000`.

---

<a name="english-version"></a>
# User Management with Flask (English Version)

## 📝 About the Project

This is a simple user management project (CRUD - Create, Read, Update, Delete) developed as part of studies on the **Flask** microframework in Python. The project was developed based on a tutorial from the **Programador Python** YouTube channel. The main goal is to apply fundamental web development concepts, such as routes, templates, and request handling.

## Features

-   **List users**: View all registered users.
-   **Register user**: Add a new user to the list.
-   **Edit user**: Update the information of an existing user.
-   **Delete user**: Remove a user from the list.
-   **View details**: Display information for a specific user in a modal.

## 💻 Technologies Used

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

-   **Backend**:
    -   **Python** and **Flask** for building routes and application logic.

-   **Frontend**:
    -   **HTML5** with **Jinja2** for structuring pages and rendering data.
    -   **CSS3** and **Bootstrap** for styling and interface responsiveness.
    -   **JavaScript (cru.js)**: Dynamic frontend interactions (like adding, editing, and deleting without a page reload) are managed by the `cru.js` library. It facilitates creating declarative AJAX requests directly in the HTML. For more information, visit the official repository: [cru.js on GitHub](https://github.com/Iazzetta/cru.js).

## 🗃️ Database

As this is a project focused on learning Flask, **we do not use a persistent database**. Data is stored in a list in the application's memory while it is running. In the future, I plan to implement integration with a database such as SQLite or PostgreSQL.

## How to Run

Follow the steps below to run the project on your local machine.

### Prerequisites

-   Python 3.x
-   pip (Python package manager)

### Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/lucascarvalho1808/gestao_usuarios_flask.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd gestao_usuarios
    ```
3.  Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

### Running the Application

To start the Flask server, run the command:

```sh
python main.py
```

The application will be available at `http://127.0.0.1:5000`.