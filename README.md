# FinanceFlow

SaaS de gestão financeira desenvolvido em Laravel.

Projeto de estudo focado em aplicar na prática os principais conceitos do Laravel: autenticação, modelagem de banco de dados, relacionamentos, CRUD e organização MVC.

🔗 [Portfólio](https://wesleyportfolio.rochabuilds.workers.dev/)

---

## 📋 Sobre o Projeto

O **FinanceFlow** é uma aplicação web para controle financeiro pessoal/empresarial.  
O objetivo é permitir que o usuário registre contas, categorize transações e acompanhe o fluxo de caixa de forma simples e organizada.

### Funcionalidades atuais

- Autenticação de usuários (registro e login)
- Cadastro e gerenciamento de contas
- Categorização de transações
- Controle de fluxo de caixa
- CRUD completo
- Modelagem de banco de dados com migrations e relacionamentos

---

## 🛠️ Tecnologias

- **Backend:** Laravel (PHP)
- **Banco de Dados:** MySQL
- **Frontend:** Blade
- **Outros:** Git

---

## 🚀 Como rodar o projeto localmente

```bash
# Clone o repositório
git clone https://github.com/Wwesley07/FinanceFlow.git

# Entre na pasta do projeto
cd FinanceFlow

# Instale as dependências
composer install

# Copie o arquivo de ambiente
cp .env.example .env

# Gere a chave da aplicação
php artisan key:generate

# Configure o banco de dados no arquivo .env
# Depois rode as migrations
php artisan migrate

# Inicie o servidor
php artisan serve
