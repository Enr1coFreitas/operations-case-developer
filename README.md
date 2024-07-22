# SubPrice Operations Case Developer

Este projeto é uma aplicação web para gerenciar produtos, incluindo funcionalidades para listar, adicionar, editar e deletar produtos. A aplicação é dividida em duas partes: backend (Node.js/Express) e frontend (React).

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- [Node.js](https://nodejs.org/) (versão 14 ou superior)
- [npm](https://www.npmjs.com/) (geralmente instalado junto com o Node.js)
- [Git](https://git-scm.com/)

## Passos para rodar o projeto

### 1. Clonar o repositório

Primeiro, clone o repositório para a sua máquina local:

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>

```

### 2. Configurar e rodar o backend

### 2.1. Navegar para o diretório do backend

```bash
cd backend

```

### 2.2. Instalar as dependências

```bash
npm install

```

### 2.3. Configurar variáveis de ambiente

Crie um arquivo `.env` na raiz do diretório `backend` e adicione as seguintes variáveis de ambiente:

```
PORT=4000

```

### 2.4. Rodar o servidor backend

```bash
npm start

```

O servidor deve estar rodando em [http://localhost:4000](http://localhost:4000/).

### 3. Configurar e rodar o frontend

### 3.1. Navegar para o diretório do frontend

Abra um novo terminal e navegue para o diretório do frontend:

```bash
cd frontend/sub-price

```

### 3.2. Instalar as dependências

```bash
npm install

```

### 3.3. Rodar o servidor frontend

```bash
npm start

```

O servidor frontend deve estar rodando em http://localhost:3000.

## Estrutura do Projeto

### Backend

O backend é um servidor Node.js usando Express para gerenciar os produtos. As principais rotas estão configuradas em `backend/routes/products.js`.

### Frontend

O frontend é uma aplicação React que utiliza Material-UI para o design dos componentes. O código principal está localizado em `frontend/sub-price/src`.

### Principais Funcionalidades

- **Listagem de Produtos**: Exibe uma lista de produtos com paginação e pesquisa por ID.
- **Adicionar Produto**: Formulário para adicionar um novo produto.
- **Editar Produto**: Formulário para editar um produto existente.
- **Deletar Produto**: Opção para deletar um produto diretamente da lista.

## Comandos Úteis

### Backend

- `npm start`: Inicia o servidor backend.
- `npm install`: Instala as dependências do backend.

### Frontend

- `npm start`: Inicia o servidor frontend.
- `npm install`: Instala as dependências do frontend.

## Autor

Feito por Enrico Freitas.

## Licença

Este projeto está licenciado sob a MIT License.

Certifique-se de substituir `<URL_DO_REPOSITORIO>` pelo URL real do repositório do Git e `<NOME_DO_REPOSITORIO>` pelo nome real do repositório.

Esse `README.md` deve fornecer instruções claras sobre como configurar e rodar o projeto tanto no backend quanto no frontend. Se precisar de mais alguma coisa ou tiver dúvidas, estou aqui para ajudar!
