# < front >Developer</ end > ao CUBO =]

Objetivo deste desafio é avaliarmos o seu domínio em front-end, ou seja, sua organização, estilo e boas práticas com o código, conhecimento dos frameworks e tecnologias utilizadas.

## Regras

1. Todo o seu código deve ser disponibilizado num repositório público ou privado em seu github ou bitbucket pessoal. Envie o link para dev@cubo.network ou faça um pull-request;  
2. Desenvolver o projeto utilizando: 
    - HTML e CSS (ou algum pré-processador); 
    - Layout responsivo;
    - Algum framework SPA (Single Page Application). Sugestão: **Angular 2**;


## O Desafio

Este é o layout que deverá ser produzido:
![layout one page](layout-onepage.png)

Aqui vai o layout em PSD:
[Download do arquivo](layout-onepage.psd)

### Dados Variáveis
Para montar a sessão **SOBRE NÓS** temos três gráficos de pizza na qual os dados devem ser obtidos atráves do método GET da API
https://of900lijd5.execute-api.us-east-1.amazonaws.com/v1/front-end/pie-chart

Para montar a sessão **DADOS** temos uma GRID e um gráfico de pizza na qual os dados devem ser obtidos atráves do método GET da API
https://of900lijd5.execute-api.us-east-1.amazonaws.com/v1/front-end/grid-people

### Algumas dicas e observações
> Obs 1.: Fique a vontade para utilizar qualquer 3rd party, seja para gráficos, testes, etc;

> Obs 2.: Abuse das animações, queremos ver seu domínio com CSS3;

> Obs 3.: Temos um formulário neste layout, considere que todos os campos são de preenchimento obrigatório e ao submeter o formulário os campos preenchidos devem ser exibidos no console (_console.log_).


## Dicas Angular 2

### install angular-cli
1. Para instalar o angular-cli você deve ter instalado antes o [Node.js](https://nodejs.org/) v4 ou superior junto com o NPM 3 ou superior.

2. Instalando o angular-cli 
    ```sh
    $ npm install -g @angular/cli
    ```

3. Faça clone deste repositório e suba o projeto

    Clone: 
    ```sh
    $ git clone https://github.com/cubonetwork/frontend-challenge.git
    ```
    Instalando as dependências:
    ```sh
    $ npm install
    ```
    Iniciando o projeto:
    ```sh
    $ npm start
    ```
    Acesse http://localhost:4200/ para visualizar o projeto base

    Rodando testes end-to-end com [Protractor](http://www.protractortest.org/):
    ```sh
    $ npm run e2e
    ```

## Dúvidas
Envie suas dúvidas diretamente para dev@cubo.network ou abrindo uma issue
