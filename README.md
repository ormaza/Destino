<p>
<img src="https://colorlib.com/preview/theme/destino/images/logo.png" alt="Logo" width="80" height="60">
  <h3>Destino</h3>
  <p>
    Sistema gerenciador de pacotes de viagens
  </p>
 </p>
 
## Conteúdo

* [Configuração](#configuração)
  * [Softwares necessários](#softwares-necessários)
  * [Pré-requisitos](#pré-requisitos)
  * [Instalação](#instalação)
* [Licença](#licença)
* [Repositório](#repositório)
* [Contato](#contato)

## Configuração
### Softwares necessários
* [NodeJs](https://nodejs.org/en/download/)
* [PostgreSQL 9.6](https://www.postgresql.org/download/)
* [.NET Core 2.2](https://dotnet.microsoft.com/download/dotnet-core)

### Pré-requisitos

* Angular CLI
```sh
npm install -g @angular/cli
```

### Instalação

1. Clone o projeto
2. Execute o postgreSQL
3. Vá até a pasta api
4. Execute os seguintes comandos
```sh
dotnet ef migrations add primeirasmigracoes --context DBViagemContext
dotnet build
dotnet run
```
5. Vá até a pasta client
6. Execute os seguintes comandos
```sh
npm install
npm start
```
7. Acesse o sistema: [Client](http://localhost:4200) e [API](http://localhost:5000)

## Licença

Este projeto foi criado com a tecnologia [CoreUI](https://coreui.io/angular/) (Documentação). Mais informações sobre sua licença clique [aqui](https://github.com/coreui/coreui-free-angular-admin-template/blob/master/LICENSE).

## Repositório

O respositório original desse projeto se encontra no [Gitlab](https://gitlab.com/imd-dev/pacote-de-viagens)

## Contato

Ormazabal Nascimento - ormazabalnascimento@gmail.com <br>
Yuri Jordan - yurirdn@ufrn.edu.br
