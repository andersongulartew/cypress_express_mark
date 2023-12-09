### Testes automatizados desenvolvidos durante o curso Cypress eXpress da QaXperience

- Criando um projeto node
- Instalando Cypress
- Executando o Cypress via interface
- Subindo API markL
#### Criando um projeto node
- Acesse a pasta de desenvolvimento
- Execute o comando abaixo:


*YARN*
 yarn init

   *NPM*
    npm init

  #### Instalando Cypress
  |  npm install cypress@12.2.0 --save-dev

  #### Executando o Cypress via interface
 Execute o comando abaixo:

*YARN*
  - yarn cypress open
    
   *NPM* 
   - npx cypress open

#### Subindo API markL
- Acesse a pasta /apps
- Execute os respectivos comandos abaixo primeiro na pasta** /api** depois na pasta **/web**
**Comandos com yarn**
1. yarn install
2. yarn db:init
3. yarn dev

 **Comandos com npm**
1. npm install
2. npm run db:init
3. npm run dev

- Após clique no **primeiro** link de http:// conforme imagem abaixo.

[![subindo-servidor](https://raw.githubusercontent.com/andersongulartew/cypress-express-mark/main/Img/subindo-servidor.png "subindo-servidor")](https://raw.githubusercontent.com/andersongulartew/cypress-express-mark/main/Img/subindo-servidor.png "subindo-servidor")
- Irá abrir automaticamente o navegador, conforme abaixo:
[![https://github.com/andersongulartew/cypress-express-mark/blob/main/Img/aplicacao.gif?raw=true](https://github.com/andersongulartew/cypress-express-mark/blob/main/Img/aplicacao.gif?raw=true "https://github.com/andersongulartew/cypress-express-mark/blob/main/Img/aplicacao.gif?raw=true")](https://github.com/andersongulartew/cypress-express-mark/blob/main/Img/aplicacao.gif?raw=true "https://github.com/andersongulartew/cypress-express-mark/blob/main/Img/aplicacao.gif?raw=true")

 **Allure**
- yarn cypress run --env allure=true
- yarn allure serve
