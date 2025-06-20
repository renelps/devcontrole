# Projeto de Gerenciamento de Chamados (Tickets)

Este projeto é uma aplicação web para gestão de chamados (tickets) e clientes. Desenvolvido com Next.js, TypeScript e Prisma, ele permite o gerenciamento completo de tickets e clientes através de uma interface moderna e funcional.

---

## 📄 Tecnologias Utilizadas

* **Next.js (App Router)**
* **TypeScript**
* **Prisma ORM**
* **NextAuth.js** (Autenticação)
* **React** (Componentização)
* **CSS Global** (pode incluir TailwindCSS)

---

## 🚀 Funcionalidades Principais

### 🔐 Autenticação

* Login de usuário com NextAuth.js
* Tipagem customizada para sessão de usuário

### 📆 Gerenciamento de Tickets

* Criação de chamados
* Listagem e visualização de tickets
* Formulários com validação para abertura de chamados

### 👥 Gerenciamento de Clientes

* Cadastro de novos clientes
* Listagem de clientes existentes
* Componentes reutilizáveis (card, formulário)

### 📊 Dashboard Interativo

* Layout organizado com cabeçalho, botões e seções distintas
* Atualização dinâmica dos dados

### 🛠️ API Routes (Back-end)

* Endpoints RESTful para:

  * Autenticação (`/api/auth`)
  * Tickets (`/api/ticket`)
  * Clientes (`/api/customer`)

---

## 📂 Estrutura de Pastas

```
/src
  |-- app
  |   |-- api              # API Routes
  |   |-- dashboard        # Dashboard de gestão
  |   |-- open             # Formulário de novo chamado
  |-- components           # Componentes reutilizáveis
  |-- lib                  # Configurações e helpers
  |-- providers            # Contextos globais (auth, modal)
  |-- utils                # Funções auxiliares
  |-- @types               # Tipagens customizadas
```

---

## 🔧 Instalação e Uso

1. Clone o repositório

```bash
git clone <repo-url>
```

2. Instale as dependências

```bash
npm install
```

3. Configure o arquivo `.env` com suas variáveis (banco de dados, autenticação, etc.)

4. Rode as migrações do Prisma

```bash
npx prisma migrate dev
```

5. Inicie o servidor

```bash
npm run dev
```

---

## 📊 Prisma

O Prisma é usado como ORM para manipulação do banco de dados. O schema se encontra em `prisma/schema.prisma`.

---

## 🔧 Utilitários

* `formatPhone.ts`: Formata números de telefone
* `date.ts`: Manipula datas para exibição

---

## 🚫 Licença

Este projeto não especifica uma licença. Sinta-se livre para adaptar conforme necessidade.

---

## 📅 Autor

Projeto desenvolvido com foco em praticar integração entre Next.js e Prisma em um ambiente de gestão de chamados.

