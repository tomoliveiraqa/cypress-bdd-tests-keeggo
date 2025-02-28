# cypress-bdd-tests-keeggo

Este repositório contém testes automatizados para o site Advantage Online Shopping utilizando Cypress, Cucumber (BDD) e JavaScript.

📌 Tecnologias Utilizadas

Cypress: Framework de testes automatizados

Cucumber (BDD): Escrita de cenários de teste em Gherkin

JavaScript: Linguagem de programação

API Testing: Testes de API usando Cypress

📂 Estrutura do Projeto

/cypress
  ├── e2e/ (testes de frontend)
  ├── component/ (testes de componentes)
  ├── plugins/
  ├── support/
  ├── fixtures/
  ├── steps/ (passos para os testes BDD)

🚀 Como Configurar e Rodar os Testes

1️⃣ Instalar as dependências

npm install

2️⃣ Executar os testes E2E

npx cypress open

3️⃣ Rodar os testes em modo headless

npx cypress run

✅ Cenários Implementados

🖥️ Testes Web

Login com credenciais válidas

Login com credenciais inválidas

Adicionar produto ao carrinho

🔗 Testes de API

Buscar detalhes de um produto

📜 Exemplo de Cenário (Gherkin)

Feature: Testes no Advantage Online Shopping

  Scenario: Usuário faz login com sucesso
    Given que o usuário acessa a página de login
    When ele insere suas credenciais válidas
    And clica no botão de login
    Then ele deve ser redirecionado para a página inicial

🤝 Contribuição

Sinta-se à vontade para abrir Issues e Pull Requests!

🚀 Projeto desenvolvido para automação de testes!

