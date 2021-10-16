# Blog

Projeto criado para aprendizado de Angular durante Bootcamp produzido pela Digital Innovation One.

Para criar o projeto foi utilizado o [Angular CLI](https://github.com/angular/angular-cli) version 10.1.4.

Após criado o projeto foi utilizado o comando npm init para criar as dependências Node Modules.

Para organizar o projeto foram organizadas as pastas em módulos. Foi criada a pasta src e dentro dela a pasta App onde foram componentizados os elementos das páginas HTML utilizando o framework Angular.

Além dos componentes foram criadas as pastas service(chamada dos métodos HTTP) e model(implementação da classe).

Para a criação dos componentes foram utilizados o comando: `ng generate component component-name`.

Na criação dos componentes podem ser utilizadas as seguintes diretivas para especificação do tipo de componente: `ng generate directive|pipe|service|class|guard|interface|enum|module`

Foram utilizadas as seguintes bibliotecas/dependências no projeto:
@angular // @fortawesome (pacote de ícones/vetores) // bootstrap // jquery // rxjs
jasmine e protactor (testes) // karma (inicialização dos métodos http)
ts-node // typescript

Para rodar o projeto localmente utilize o comando: npm run start

O projeto irá abrir no navegador no seguinte endereço:`http://localhost:4200/`


Para mais informações sobre o Angular acesse: [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

