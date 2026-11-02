# Consulta de Vendas — React + TypeScript

Projeto desenvolvido como exercício prático durante os estudos de React e TypeScript na Origamid.

A aplicação consome uma API REST para consultar vendas de acordo com um período selecionado pelo usuário, exibindo o nome e o status de cada transação.

## 🎯 Objetivo

Praticar o gerenciamento de estados no React, a utilização de efeitos colaterais com `useEffect` e o consumo de uma API externa utilizando TypeScript.

## ✨ Funcionalidades

- Seleção de data inicial e data final.
- Atualização dos estados conforme a alteração dos campos.
- Consulta de vendas por período.
- Consumo de dados de uma API REST utilizando Fetch API.
- Exibição do nome e status das vendas retornadas.
- Renderização dinâmica dos resultados na interface.

## 🛠️ Tecnologias utilizadas

- **React** — construção da interface e gerenciamento de estados.
- **TypeScript** — tipagem de dados e maior segurança no desenvolvimento.
- **JavaScript** — lógica e manipulação de dados.
- **HTML5** — estrutura da aplicação.
- **CSS3** — estilização.
- **Fetch API** — requisições HTTP.
- **Git e GitHub** — versionamento do código.

## 📚 Conceitos praticados

- `useState`: gerenciamento de estados reativos.
- `useEffect`: execução de efeitos quando as datas são alteradas.
- Componentização e reutilização de componentes.
- Tipagem de dados com TypeScript.
- Consumo de API REST.
- Promises e tratamento de erros com `catch`.
- Renderização condicional.
- Renderização de listas com `map`.
- Props e comunicação entre componentes.

## 🔗 API utilizada

API disponibilizada pela Origamid:

https://data.origamid.dev/vendas/

A consulta utiliza os parâmetros `inicio` e `final`, no formato `YYYY-MM-DD`.

Exemplo:

```text
https://data.origamid.dev/vendas/?inicio=2026-10-01&final=2026-10-15
```

A API disponibiliza dados de hoje até os últimos 90 dias.

## ▶️ Como executar o projeto

### Pré-requisitos

- Node.js instalado.
- npm instalado.
- Visual Studio Code ou outro editor de código.

### Instalação

1. Clone o repositório:

   ```bash
   git clone  https://github.com/mi2507/useState-tsx.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd React-TS 
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Acesse o endereço informado no terminal, normalmente `http://localhost:5173`.

## 🎓 Sobre o projeto

Exercício educacional desenvolvido para consolidar conhecimentos em React, TypeScript e integração com APIs REST, utilizando componentes reutilizáveis e gerenciamento de estados.

## 👩‍💻 Autora

**Michelle Regina da Silva**

GitHub: https://github.com/mi2507
