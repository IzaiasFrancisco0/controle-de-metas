# 🎯 Controle de Metas — CLI

Aplicação de **linha de comando (CLI)** desenvolvida com **Node.js** para gerenciamento de metas.

O projeto permite cadastrar, visualizar, concluir e excluir metas diretamente pelo terminal, utilizando operações CRUD e armazenamento dos dados em arquivo JSON.

## 🚀 Funcionalidades

* ➕ Cadastrar novas metas
* 📋 Listar metas
* ✅ Marcar metas como concluídas
* 📊 Visualizar metas realizadas
* 📌 Visualizar metas em aberto
* 🗑️ Excluir metas
* 💾 Persistência dos dados em arquivo JSON

## 🛠️ Tecnologias

* **Node.js**
* **JavaScript**
* **@inquirer/prompts**
* **JSON**
* **File System (fs)**

## 🧠 Conceitos praticados

* Operações CRUD
* Programação assíncrona com `async/await`
* Manipulação de arquivos com `fs`
* Leitura e escrita de arquivos JSON
* Estruturas de dados
* Funções e modularização
* Tratamento de entradas do usuário
* Interação com o terminal
* Gerenciamento de dependências com NPM

## 📂 Estrutura

```text
Controle-De-Metas/
├── index.js
├── metas.json
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## ⚙️ Pré-requisitos

Para executar o projeto, é necessário ter o **Node.js** instalado.

Verifique a instalação:

```bash
node --version
npm --version
```

## 📥 Instalação

Clone o repositório:

```bash
git clone https://github.com/IzaiasFrancisco0/Controle-De-Metas.git
```

Entre no diretório:

```bash
cd Controle-De-Metas
```

Instale as dependências:

```bash
npm install
```

## ▶️ Executando o projeto

Inicie a aplicação com:

```bash
node index.js
```

O sistema apresentará um menu interativo no terminal:

```text
? Menu >
❯ Cadastrar meta
  Listar metas
  Metas realizadas
  Metas abertas
  Deletar metas
  Sair
```

A navegação é realizada utilizando as **setas do teclado** e a tecla **Enter**.

## 💾 Armazenamento

As metas são armazenadas no arquivo:

```text
metas.json
```

O arquivo é atualizado automaticamente conforme as operações realizadas na aplicação.

Exemplo:

```json
[
  {
    "value": "Correr 5km todos os dias",
    "checked": true
  },
  {
    "value": "Estudar Node.js",
    "checked": false
  }
]
```

