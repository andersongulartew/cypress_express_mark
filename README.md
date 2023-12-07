# cypress-express-mark
Testes automatizados desenvolvidos durante o curso Cypress eXpress da QaXperience


Criando um projeto node
Instalando Cypress
Executando o Cypress via interface
Subindo API markL
Criando um projeto node
Acesse a pasta de desenvolvimento
Execute o comando abaixo:
YARN	NPM
yarn init	npm init
Instalando Cypress
npm install cypress@12.2.0 --save-dev

Executando o Cypress via interface
Execute o comando abaixo:
YARN	NPM
yarn cypress open	npx cypress open
Subindo API markL
Acesse a pasta /apps
Execute os respectivos comandos abaixo primeiro na pasta /api depois na pasta /web
Comandos com yarn
1. yarn install
2. yarn db:init
3. yarn dev
Comandos com npm
1. npm install
2. npm run db:init
3. npm run dev
Após clique no primeiro link de http:// conforme imagem abaixo.
📸
Irá abrir automaticamente o navegador, conforme abaixo:
📸
Allure
yarn cypress run --env allure=true
yarn allure serve
