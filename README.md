# 🔌 API REST PHP + MySQL

API REST desenvolvida em **PHP** para gerenciamento de dados relacionais, implementando CRUD completo, validações e organização do código com os padrões **MVC** e **DAO**.

## 🚀 Funcionalidades

- Criação, consulta, atualização e exclusão de registros
- Relacionamentos entre entidades no banco de dados
- Validação de dados e regras de negócio
- Requisições e respostas em JSON
- Métodos HTTP `GET`, `POST`, `PUT/PATCH` e `DELETE`
- Organização da aplicação em camadas

## 🏗️ Arquitetura

```text
Requisição HTTP
      ↓
    Routes
      ↓
 Controllers
      ↓
  Services
      ↓
     DAO
      ↓
    MySQL
```

A aplicação utiliza **MVC** para separar responsabilidades e **DAO** para concentrar as operações de acesso ao banco de dados.

## 🛠️ Tecnologias e conceitos

- PHP
- Slim Framework 4
- MySQL
- PDO
- Composer
- API REST
- JSON
- MVC
- DAO

## 📡 Documentação da API

Os endpoints e exemplos de requisições estão documentados em [`API.md`](./API.md).

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/VitorHens/api-rest-php-mysql.git
cd api-rest-php-mysql
```

### 2. Instale as dependências

```bash
composer install
```

### 3. Configure o banco de dados

Prepare o MySQL conforme a estrutura utilizada pelo projeto antes de iniciar a API.

### 4. Inicie o servidor

```bash
composer start
```

Ou diretamente:

```bash
php -S localhost:8080 -t public
```

## 🧪 Testes da API

Os endpoints podem ser testados com ferramentas como **Insomnia** ou **Postman**.

## 📁 Estrutura principal

```text
├── public/             # Ponto de entrada da aplicação
├── src/                # Código-fonte da API
├── docs/               # Documentação complementar
├── API.md              # Endpoints e exemplos
├── composer.json       # Dependências e scripts
└── composer.lock       # Versões das dependências
```

## 🎯 Objetivo

Praticar desenvolvimento de APIs REST, modelagem de banco de dados relacional e organização de aplicações back-end com padrões de projeto.

Projeto desenvolvido durante a disciplina de PAW.

---

Desenvolvido por **Vitor Hens**.
