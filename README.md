Para o desenvolvimento deste curso foi utilizada a ferramente ESLint.
Primeiros passos. 
Iniciar um projeto npm com o comando 'npm init -y' que gera um arquivo package.json. Dentro do pacote, você encontrará metadados específicos para o projeto.

{
  "name": "teste-unitario",
  "verion": "1.0.0",
  "description": "",
  "main":"index.js",
  "scripts": {
    "teste": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license":"ISC",
  "devDependencies": {
    "eslint": "^8.47.0",
    "eslint-config-airbnb-base": "^15.0.0",
    "eslint-plugin-import": "^2.28.1"
  }
}

  O nome é teste-unitario;
  A versão é 1.0.0;
  O ponto de entrada do projeto ou o arquivo principal é index.js;
  As palavras chave ou tags para encontrar o projeto no repositório são npm, exemplo e teste;
  Este projeto está licenciado sob o ISC;
  As dependências ou outros módulos que esse módulo usa são "eslint": "^8.47.0".

Segundo passo
Instalar ESLint com o comando 'npm init @eslint/config'.