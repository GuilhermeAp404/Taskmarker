![Badge de Status](https://img.shields.io/badge/status-produção-green)
# TaskMarker
> Um aplicativo organizacional para registro e gerenciamento de tarefas diárias. 

## 📋 Índice  
- [Sobre o Projeto](#-sobre-o-projeto)  
- [Demonstração](#-demonstração)  
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)  
- [Instalação e Uso](#-instalação-e-uso)  
- [Contato](#-contato) 

## 💡 Sobre o Projeto  
O **TaskMarker** foi criado com o intuito de ser uma aplicação organizacional, permitindo que os usuários registrem e gerenciem suas tarefas diárias, definindo horários de início e término para melhor controle da produtividade.  

## 🚀 Demonstração  
![Tela de registro](/assets/registro.png)
![Tela de login](/assets/login.png)


### 🔗 [Acesse a aplicação](https://taskmarker-kappa.vercel.app/)

## 🛠 Tecnologias Utilizadas  
O projeto foi desenvolvido com as seguintes tecnologias:  

- [Express](https://expressjs.com/pt-br/)
- [Sequelize](https://sequelize.org/)
- [MySQL](https://www.mysql.com/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [React Hook Form](https://www.react-hook-form.com/)
- [Axios](https://axios-http.com/ptbr/docs/intro)
- [Context API](https://react.dev/reference/react/useContext)
- [TailwindCSS](https://tailwindcss.com/)


## 📦 Instalação e Uso  

### Pré-requisitos  
Antes de começar, certifique-se de ter as seguintes ferramentas instaladas:  
- [Node.js](https://nodejs.org/)  
- [Yarn](https://yarnpkg.com/) ou [npm](https://yarnpkg.com/) 

### Clonar o repositório

#### Iniciar o backend
##### Instalar todas as dependências
Execute os comandos na seguinte ordem:
```sh
git clone https://github.com/seu-usuario/taskmarker.git
cd taskmarker 

cd backend

yarn install  
# ou npm install
```
##### Criar um arquivo .env
Utilize as seguintes variáveis:

```sh
NODE_ENV="production"
PORT= 3333
PRIVATE_KEY="chave_privada_aqui"
ORIGIN_URL="http://localhost:3000"

DB_USERNAME="root"
DB_PASS=""
DB_DATABASE="taskmarker"
DB_HOST="localhost"
DB_PORT="3306"
DB_DIALECT="mysql"
```
**Atenção:** certifique-se que existe um banco com o nome "taskmarker" já criado

##### Iniciar o projeto
```sh
npm run dev
# ou
npm start 

#caso queira usar o yarn

yarn dev  
# ou 
yarn start
```


#### Iniciar o frontend

##### Instalando as dependências
Entre na pasta frontend e digite os seguinte comandos:
```sh
yarn install  
# ou npm install
```

##### Criar um arquivo .env
Utilize as seguintes variáveis:

```sh
REACT_APP_API = 'http://localhost:3333'
```

##### Iniciar o projeto
```sh
npm start 
# ou 
yarn start
```

## 📬 Contato
📧 Email: guilherme.ap404@gmail.com
🌎 LinkedIn: https://www.linkedin.com/in/guilherme-faria-dev/