# 🧰 Sistema Gerenciador de Estoque de Oficina

## 📘 Descrição Geral

O **Sistema Gerenciador de Estoque de Oficina** tem como objetivo otimizar o controle de produtos e materiais utilizados em uma oficina mecânica.  
A aplicação busca garantir que **mecânicos, gerentes e demais colaboradores** tenham acesso fácil e atualizado às informações do estoque, possibilitando uma **gestão eficiente das compras e do uso de itens**.

---

## ⚙️ Tecnologias Utilizadas

### Front-end
- **React** – Biblioteca JavaScript para construção de interfaces dinâmicas e reativas.  
- **TypeScript** – Superset do JavaScript com tipagem estática, aumentando a segurança e previsibilidade do código.  
- **Tailwind CSS** – Framework CSS utilitário que facilita a criação de interfaces modernas e responsivas.

### Back-end
- **Node.js** – Ambiente de execução JavaScript voltado para aplicações escaláveis.  
- **FastAPI** – Framework moderno em Python para construção de APIs de alta performance.

### Banco de Dados
- **PostgreSQL** – Banco de dados relacional robusto e de código aberto.

### Versionamento
- **Git** e **GitHub** – Controle de versão e hospedagem do repositório do projeto.

---

## 🧩 Arquitetura do Projeto

O projeto segue a arquitetura **FSD (Feature-Sliced Design)**, uma abordagem moderna para estruturar aplicações front-end de forma modular e escalável.

Essa arquitetura propõe a divisão do sistema em **camadas e fatias (slices)** que representam funcionalidades específicas, facilitando a manutenção e a evolução do código.
```bash
src/
├── app/ # Configurações globais da aplicação (rotas, providers, etc.)
├── entities/ # Entidades principais do domínio (ex: Produto, Colaborador)
├── features/ # Funcionalidades específicas (ex: Cadastro, Login, etc.)
├── shared/ # Componentes e utilitários reutilizáveis
└── widgets/ # Blocos visuais que compõem as páginas
```

> **Objetivo:** Manter o código organizado, modular e escalável, permitindo o desenvolvimento independente de cada parte da aplicação.
---

## 🚀 Como Executar o Projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/danielpedroo/project_autopartsmanager.git
````

2️⃣ Acessar o diretório do projeto
```bash
cd autopartsmanager
```

3️⃣ Instalar as dependências do front-end
```bash
npm install
# ou
yarn install
```

4️⃣ Rodar o front-end
```bash
npm run dev
# ou
yarn dev
```

👤 Autor
Desenvolvido por Daniel Pedro
