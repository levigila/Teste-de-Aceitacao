# Testes de Aceitação - Buger Eats

Este repositório contém testes de aceitação escritos com o framework Cypress para validar o comportamento da aplicação Buger Eats.

## **Visão Geral**

Os testes de aceitação são uma parte essencial do processo de garantia de qualidade de software, pois verificam se a aplicação atende aos requisitos e expectativas do usuário final. Este projeto concentra-se em testes de aceitação para a aplicação Buger Eats, garantindo que a mesma esteja funcionando conforme o esperado para os usuários.

## **Testes Incluídos**

- **Página Online**: Verifica se a página inicial do sistema está online e acessível para os usuários.

## **Estrutura do Projeto**

O projeto está estruturado da seguinte forma:

- `cypress/integration`: Contém os arquivos de teste Cypress, organizados por funcionalidade ou cenário.
- `cypress/support`: Contém arquivos de suporte, como comandos personalizados ou configurações globais.
- `cypress.json`: Arquivo de configuração do Cypress.

## **Executando os Testes**

Para executar os testes, siga as etapas abaixo:

1. Certifique-se de ter o Node.js e o npm instalados em seu ambiente.
2. Clone este repositório em sua máquina local.
3. Navegue até o diretório do projeto e execute o seguinte comando para instalar as dependências:

   ```
   npm install
   ```

4. Após a instalação das dependências, execute o seguinte comando para iniciar os testes:

   ```
   npm test
   ```

Este comando iniciará o Cypress e executará todos os testes de aceitação incluídos no projeto, exibindo os resultados no terminal e também em uma interface gráfica interativa.
