# dsmeta-devsuperior
Sistema desenvolvido durante a Semana Spring React 10ª edição, feito pela DevSuperior.

## Tecnologias utilizadas
- Java 11
- Framework Spring (Spring Web, Spring Data JPA, Spring Security)
- Banco de Dados H2
- HTML
- CSS
- Typescript
- React
- Twilio API (para envio de SMS)

## Como executar
- Backend
  - Importar como um projeto Maven na IDE Eclipse, Spring Tool Suite, IntelliJ ou outra IDE de sua preferência.
  - Automaticamente serão baixadas as dependências do projeto.
  - Feito isso poderá startar a aplicação pela sua IDE.
- Frontend
  - Abrir no Visual Studio Code ou algum editor de texto de sua preferência.
  - Abra o terminal (no diretório do projeto) e digite o comando "yarn" (sem as aspas) para baixar as dependências do projeto.
  - Para executar a aplicação basta executar o comando: yarn dev

## Endpoints
- http://localhost:8080/sales (traz a lista de vendas)
- http://localhost:8080/sales?minDate=2021-11-01&maxDate=2022-03-31 (traz a lista de vendas em determinado período)
- http://localhost:8080/sales/53/notification (envia uma notificação relacionada ao ID de uma determinada venda).
