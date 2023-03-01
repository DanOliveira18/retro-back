
# Node JS template

This is my template to start a nodeJS project using typescript, it implements 
some libraries to help the development process and easily start a new project. 

**Warning:** this template come with express installed, if you wont use it, remove it from src/server.ts and src/routes.ts and uninstall the following dependencies before init the Development server.

```bash
  yarn remove express @types/express
```

## Main libraries

 - **Typescript**  

 - **TS-node-dev**

 - **Es-lint**

 - **Jest**

 - **Babel**

 - **Docker**

  - **Yarn**
## Development server

You can run this project locally or using docker, both will create a live server, that is, you dont need to restart the server after doing some changes, I recommend use docker if you will need a database, and add it configuration to docker-compose.yml.

First clone the repo.

```bash
  git clone https://github.com/DanOliveira18/node-ts-template.git
  cd node-ts-template
```

### Locally

Install dependecies and use dev command to start the development server

```bash
  yarn install
  yarn dev
```


### Docker

Using docker you just need to up the container

```bash
  sudo docker compose up -d --build
```
