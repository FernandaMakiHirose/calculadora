# Construindo uma Calculadora com o Angular
## Como criei o projeto?
Criar o projeto:
>ng new calculadora

Entrar no projeto:
>cd calculadora

## Após clonar o projeto, digite no terminal
NPM:
>npm install

Instalar o Bootstrap
>npm install --save bootstrap@3

Executar um teste:
>ng test

Executar o projeto:
>ng serve

## Como criou um módulo?
>ng g module calculadora

## Como criou um componente?
>ng g component calculadora/calculadora

## Como criou um serviço?
>ng g service calculadora/services/calculadora

## Entendendo o código
`app.module.ts`: É necessário fazer a importação de todos os módulos <br>
`calculadora.module.ts`: Exportação dos componentes com o "exports" e tem o "providers" que tem os serviços injetados em outros componentes. <br>
`services`: Os serviços apresentam o @Injectable(), onde é possível fazer a injeção de dependência <br>
`index.ts`: O código faz com que não seja preciso passar o nome da classe na importação dos módulos no arquivo `app.module.ts` <br>

