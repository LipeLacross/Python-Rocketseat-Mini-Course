## 🌐 [English Version of README](README_EN.md)

# Python-Rocketseat-Mini-Course
# E-commerce Flask Application

Este é um aplicativo de e-commerce desenvolvido com Flask. Ele permite a criação e gerenciamento de produtos, autenticação de usuários e operações de carrinho de compras.

## 🔨 Funcionalidades do Projeto

- **Autenticação de Usuários**:
    - Registro e login de usuários.
    - Gerenciamento de sessões e logout.

- **Gerenciamento de Produtos**:
    - Adicionar, atualizar, visualizar e excluir produtos.

- **Carrinho de Compras**:
    - Adicionar e remover itens do carrinho.
    - Visualizar o conteúdo do carrinho.
    - Realizar checkout e limpar o carrinho.

### Exemplo Visual do Projeto

![Screenshot 2024-09-11 183553](https://github.com/user-attachments/assets/8737a026-d079-4e64-a6c5-5c983c41f80d)
![Screenshot 2024-09-11 184640](https://github.com/user-attachments/assets/8c3d7381-c9fd-434c-bb83-79fd9fb91947)
![Screenshot 2024-09-11 185002](https://github.com/user-attachments/assets/c4d99af3-80a5-4093-a7f4-7af4215d2911)
![Screenshot 2024-09-11 185615](https://github.com/user-attachments/assets/368cd3d3-8902-435d-9515-a5641d87a9c2)
![Screenshot 2024-09-11 185555](https://github.com/user-attachments/assets/5f531acd-9d85-4a40-849b-18d009ad4473)
![Screenshot 2024-09-11 185320](https://github.com/user-attachments/assets/ebccd156-35b1-486a-86a8-c08d0e9f60c5)

Para visualizar o aplicativo, acesse a URL local em `http://127.0.0.1:5000` após iniciar o servidor.

## ✔️ Técnicas e Tecnologias Utilizadas

- **Flask**: Framework web para criar o aplicativo.
- **Flask-SQLAlchemy**: ORM para interagir com o banco de dados SQLite.
- **Flask-Login**: Gerenciamento de sessões e autenticação de usuários.
- **Flask-Cors**: Suporte a CORS para permitir requisições entre diferentes domínios.
- **SQLite**: Banco de dados usado para armazenar informações de produtos, usuários e carrinho de compras.

## 📁 Estrutura do Projeto

- **app.py**: Arquivo principal do aplicativo Flask, contém a definição das rotas e lógica de negócios.
- **ecommerce.db**: Banco de dados SQLite que armazena usuários, produtos e itens do carrinho.
- **requirements.txt**: Lista das dependências do projeto.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Python está instalado**:
    - O [Python](https://www.python.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:

      ```bash
      python --version
      ```

    - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Crie e ative um ambiente virtual**:
    - Crie um ambiente virtual com o comando:

      ```bash
      python -m venv .venv
      ```

    - Ative o ambiente virtual:
        - No Windows:

          ```bash
          .venv\Scripts\activate
          ```

        - No macOS e Linux:

          ```bash
          source .venv/bin/activate
          ```

3. **Instale as dependências**:
    - Execute o comando abaixo para instalar as dependências listadas em `requirements.txt`:

      ```bash
      pip install -r requirements.txt
      ```

4. **Inicie o servidor**:
    - Execute o comando abaixo para iniciar o servidor Flask:

      ```bash
      python app.py
      ```

    - O aplicativo estará disponível em `http://127.0.0.1:5000`.

5. **Acesse o aplicativo**:
    - Abra um navegador e vá para `http://127.0.0.1:5000` para interagir com o aplicativo.

## 🌐 Deploy

Para realizar o deploy do aplicativo em um servidor de produção, siga as etapas apropriadas para o servidor escolhido. Configure o servidor para usar o WSGI (como Gunicorn ou uWSGI) e um servidor web reverso (como Nginx) para garantir a operação eficiente e segura do aplicativo.


