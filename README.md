# Projeto
Esse é um projeto com framework Playwright, aplicação que estamos utilizando para automação é https://buger-eats.vercel.app/
Para ter uma visualização de como o projeto foi evoluindo, acesse o histórico de commits.

# Instalar dependências
1. Após clonar o projeto, acessar a pasta raiz e instalar as dependências através do comando: npm install

# Execução dos testes
Os testes podem ser executados através dos scripts criados no arquivo package.json:
npm run testes
Outras formas de execução podem ser encontradas nas documentações https://playwright.dev/docs/running-tests

Os testes estão sendo executados em 3 browsers (chromium, firefox e webkit) conforme arquivo playwright.config.js

A execução está ocorrendo em modo headless: true, dessa forma o browser não será aberto. Caso queira visualizar, no arquivo playwright.config.js, mudar headless: false.

# Biliotecas externas
Faker BR
https://www.npmjs.com/package/faker-br
O faker BR é utilizado para criar os dados de usuário e endereço.