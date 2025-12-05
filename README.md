# QA-Cypress
#  Automação de Testes Web - AutomationExercise
O teste automatizado cobre o seguinte fluxo:

1. **Acesso ao site** AutomationExercise
2. **Cadastro de novo usuário** com dados válidos
3. **Navegação** para página de produtos
4. **Seleção e adição** de produto ao carrinho
5. **Processo de checkout** com verificação de dados
6. **Finalização do pedido** com pagamento
7. **Confirmação** do pedido realizado

### Gestão de Testes

- **Ferramenta:** [Testomat.io](https://testomat.io)
- **Casos de Teste:** 21 casos distribuídos em 7 suítes
- **Execução Manual:** Realizada com evidências (screenshots)
- **Relatório:** Gerado em PDF com resultados



###  **Arquitetura**

- **Features:** Cenários escritos em Gherkin (BDD)
- **Step Definitions:** Implementação dos passos em JavaScript
- **Page Objects:** Encapsulamento de elementos e ações das páginas
- **Fixtures:** Dados de teste reutilizáveis
- **Commands:** Comandos customizados do Cypress

## Instalação e Configuração

**Pré-requisitos**

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [Git](https://git-scm.com/)
- npm ou yarn

### 🔧 **Passos de Instalação**

1. **Clone o repositório:**
```bash
git clone https://github.com/SEU_USUARIO/automacao-exercise-web.git
cd automacao-exercise-web
Instale as dependências:
bash
Copiar

npm install
Verifique a instalação:
bash
Copiar

npx cypress verify


 Scripts Disponíveis
Comando	Descrição
npm run cypress:open	Abre interface gráfica
npm run cypress:run	Execução headless
npm test	Executa todos os testes

## Cenário Principal: Fluxo Completo de Pedido
Feature: Fluxo de realização de pedido
  Como um cliente
  Eu quero realizar um pedido completo
  Para comprar produtos no site

  Scenario: Realizar pedido completo com novo usuário
    Given que acesso o site AutomationExercise
    When realizo cadastro de novo usuário
    And navego até a página de produtos
    And seleciono um produto e adiciono ao carrinho
    And procedo para o checkout
    And preencho dados de entrega
    And confirmo o pedido
    Then devo ver a confirmação do pedido realizado



Tecnologias Utilizadas
Cypress - Framework de testes E2E
Cucumber - BDD (Behavior Driven Development)
JavaScript - Linguagem de programação
Page Object Model - Padrão de design
    And procedo para o checkout
    And preencho dados de entrega
    And confirmo o pedido
    Then devo ver a confirmação do pedido realizado
