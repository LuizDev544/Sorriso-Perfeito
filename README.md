# SorrisoPerfeito - Sistema Abrangente de Gestão de Consultas Odontológicas 🦷

O **SorrisoPerfeito** é uma aplicação web desenvolvida para gerenciar consultas odontológicas, registros de usuários e tarefas administrativas. Ele oferece uma interface amigável para que os clientes visualizem suas consultas e para que os administradores gerenciem agendas e atendimentos. A aplicação foi construída utilizando PHP, MySQL e Bootstrap, garantindo uma solução robusta e escalável.

## 🚀 Funcionalidades
* Funcionalidade de login e registro de usuários.
* Painel do cliente para visualizar consultas agendadas.
* Painel administrativo para gerenciar consultas e horários.
* Formulário para adicionar novas consultas.
* Esquema de banco de dados para armazenar e gerenciar dados.
* Conexão segura com o banco de dados usando a extensão MySQLi.
* Design responsivo utilizando Bootstrap CSS e JavaScript.

## 🛠️ Tecnologias Utilizadas
* **Frontend:** PHP, Bootstrap CSS, Bootstrap JavaScript
* **Backend:** PHP, MySQL
* **Banco de Dados:** MySQL
* **Servidor:** Apache
* **Dependências:** Extensão MySQLi, bibliotecas Bootstrap CSS e JavaScript

## 📦 Instalação
Para instalar a aplicação, siga estas etapas:
1. Clone o repositório para sua máquina local.
2. Crie um novo banco de dados e importe o arquivo `DatabaseSorriso.sql`.
3. Atualize o arquivo `Database.php` com as credenciais do seu banco de dados.
4. Instale as dependências necessárias, incluindo a extensão MySQLi e as bibliotecas do Bootstrap.
5. Configure seu servidor Apache para apontar para o arquivo `index2.php`.

## 💻 Como Usar
1. Abra um navegador web e navegue até a URL da aplicação.
2. Registre-se como um novo usuário ou faça login com uma conta existente.
3. **Como cliente:** Visualize suas próximas consultas no painel do cliente.
4. **Como administrador:** Gerencie consultas e agendas no painel administrativo.
5. Adicione novas consultas utilizando o formulário fornecido.

## 📂 Estrutura do Projeto
```markdown
MVC
├── controller
│   ├── ConsultaController.php
│   ├── RegistroController.php
├── model
│   ├── Consulta.php
│   ├── Database.php
│   ├── ModelLogin.php
├── view
│   ├── index2.php
│   ├── AdicionarConsulta.php
│   ├── PainelCliente.php
│   ├── PainelAdm.php
├── DatabaseSorriso.sql
