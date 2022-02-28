# FrontEndSpring

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


## Deploy Heroku API
- Fazer cadastro na Heroku
- create a new app
  - nome
  - região
  - create app
- Deployment method
  - github
  - connect github
  - escolhe o repositório
  - habilitar deploy automático
  - escolhe a branch
- Na API na raiz
  - Espeficicar a versõa do JDK
  - crie um arquivo *system.properties*
```
java.runtime.version=11
```
- Mudar @CrossOrigin para a URL do frontend
## Deploy GITHUB Pages
- nome-od-usuario.github.io
- muda a url de produção da API
- ng build --prod
- o build será gerado na pasta dist
- copie a pasta que está dentro de dist
- renomeie para docs e coloqe na raiz
- após subir a aplicação
  - vá em settings
  - github pages
    - em source, selecione docs
  
