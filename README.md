<h1 align="center">
  🛒 Site da Felicidade
</h1>

<p align="center">
  <strong>Um sistema completo de e-commerce desenvolvido com Python e Django.</strong>
</p>

<p align="center">
  <em>Desenvolvido por: Kevin Flay Vieira de Oliveira</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/0Y7fw4Z.png" alt="Screenshot da tela inicial do site" width="80%">
</p>

---

## 📋 Sobre o Projeto

O **Meu Site Bacana** é uma plataforma de vendas online criada como projeto para a disciplina de Desenvolvimento Web III. O sistema simula um ambiente de e-commerce real, com funcionalidades de cadastro de produtos, gestão de usuários, carrinho de compras e um painel administrativo para visualização de métricas de vendas e estoque.

---

## ✨ Funcionalidades Principais

* **Gestão de Usuários:** Sistema completo de CRUD (Criar, Ler, Atualizar, Excluir) para usuários.
* **Autenticação:** Mecanismo de Login e Logout seguro com controle de sessão.
* **Catálogo de Produtos:** CRUD completo para produtos, incluindo nome, descrição, preço, estoque e imagem.
* **Página de Vendas:** Galeria de produtos com design responsivo, separando itens em destaque dos demais.
* **Checkout Simplificado:** Processo de finalização de compra com formulário para dados de pagamento.
* **Dashboard Administrativo:** Painel de controle para administradores com atalhos para as principais funcionalidades.
* **Visualização de Dados:** Gráficos dinâmicos para análise de estoque e total de vendas por dia.
* **Integração com API Externa:** Preenchimento automático de endereço no cadastro de usuário através da API ViaCEP.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

* **Backend:** Python, Django
* **Frontend:** HTML5, CSS3, JavaScript
* **Framework CSS:** Bootstrap 5
* **Banco de Dados:** SQLite 3
* **Visualização de Dados:** Chart.js
* **Imagens:** Pillow
* **API:** ViaCEP

---

## 🚀 Como Executar o Projeto

Para rodar este projeto localmente, siga os passos abaixo. É recomendado o uso de um ambiente virtual.

1.  **Clone o repositório (ou use os arquivos locais) e crie um ambiente virtual:**
    ```bash
    # Cria o ambiente virtual
    python -m venv venv

    # Ativa o ambiente (Windows)
    .\venv\Scripts\activate

    # Ativa o ambiente (Linux/Mac)
    source venv/bin/activate
    ```

2.  **Instale as dependências necessárias:**
    ```bash
    pip install django pillow
    ```

3.  **Aplique as migrações do banco de dados:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

4.  **Crie um superusuário para acessar o painel de administração:**
    ```bash
    python manage.py createsuperuser
    ```
    *Você precisará informar um nome de usuário, e-mail e senha.*

5.  **Inicie o servidor de desenvolvimento:**
    ```bash
    python manage.py runserver
    ```

6.  **Acesse o projeto no seu navegador:**
    * **Site:** `http://127.0.0.1:8000/`
    * **Admin:** `http://127.0.0.1:8000/admin/`

---
