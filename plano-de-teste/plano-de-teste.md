# **Plano de Testes \- Aplicativo de Delivery**

* **Nome do Projeto:** 

* ### **Versão do Plano de Teste:** 1.0

* **Data de Criação:** 26/11/2024

* **Data de Revisão:** 03/12/2024

* **Nome do Gerente de Testes:** Victor Barbosa

* **Equipe de Testes:** \[inserir nomes dos testadores\]

## 1. **Escopo e Objetivo Descrição:**

O escopo reflete as funcionalidades e limites do aplicativo, enquanto o objetivo foca na finalidade do aplicativo de delivery, ajudando a contextualizar melhor o plano de testes.

### **Exemplo para o App de Delivery:**

O aplicativo tem como objetivo facilitar a interação entre clientes e restaurantes locais, permitindo que os usuários encontrem rapidamente opções de refeição, façam o pedido com praticidade e acompanhem a entrega em tempo real. Além disso, o sistema busca fornecer uma plataforma confiável para transações financeiras e manter os usuários informados sobre o status de seus pedidos por meio de notificações.

## 2. **Características do Produto a Serem Testadas Descrição:**

As funcionalidades e características que serão validadas durante o processo de testes. Aqui serão listadas as principais funcionalidades que precisam ser testadas no aplicativo.

### **Exemplo para o App de Delivery:**

* login
* 

## 3. **Abordagem a Ser Utilizada Descrição:**

A abordagem de teste define quais técnicas, métodos e ferramentas serão usadas no processo. Ela ajuda a garantir a cobertura adequada das funcionalidades.

| Item | Descrição |
| :---- | :---- |
| **Objetivo** | Descreva aqui o objetivo. |
| **Técnica** | (x) Manual (x) Automática |
| **Estágio do Teste** | Integração ( ) Sistema ( ) Unidade (x) Aceitação ( ) |
| **Abordagem do Teste** | Caixa Branca (x) Caixa Preta (x) |
| **Responsável(is)** | Programador(es) ou equipe de testes |

### **Exemplo para o App de Delivery (Tipos de Testes):**

* **Testes Funcionais:** Testar todas as funções principais do aplicativo (criação de conta, login, pedidos, pagamentos).

  * **Testes de Usabilidade:** Avaliar a facilidade de uso da interface, navegabilidade e clareza das informações.

  * **Testes de Desempenho:** Avaliar o tempo de resposta durante picos de uso, como promoções ou horários de almoço/jantar.

  * **Ferramentas Utilizadas:** Selenium (para automação), JMeter (para testes de desempenho).

## 4. **Itens a Serem Testados Descrição:**

Os componentes do sistema que serão testados, desde funcionalidades até módulos específicos.

### **Exemplo para o App de Delivery:**

* Validação dos processos de criação de conta, login e recuperação de senha.

  * Testar a funcionalidade de pesquisa por restaurantes baseados em localização e filtros.

  * Garantir que o usuário consiga adicionar/remover itens, verificar preços e finalizar compras.

  * Acompanhar a mudança de status do pedido (aceito, em preparo, a caminho, entregue).

  * Verificar a integração com gateways de pagamento e confirmação de transações.

## 5. **Cronograma para o Teste Descrição:**

O cronograma estabelece o tempo estimado para a execução de cada etapa do plano de testes.

### **Exemplo para o App de Delivery:**

* **Semana 1:** Revisão do plano de testes e preparação do ambiente.

  * **Semana 2-3:** Execução de testes funcionais nas funcionalidades de login e busca de restaurantes.

  * **Semana 4:** Execução de testes de desempenho com simulações de carga.

  * **Semana 5:** Regressão e testes de usabilidade.

  * **Semana 6:** Avaliação final, relatório de bugs e liberação para produção.

## 6. **Pessoal Responsável pelas Diferentes Atividades de Teste Descrição:**

Lista dos testadores responsáveis por cada atividade ou parte do processo de testes.

### **Exemplo para o App de Delivery:**

* **Responsável por Testes Funcionais:** João Silva

  * **Responsável por Testes de Desempenho:** Maria Souza

  * **Responsável por Automação de Testes:** Pedro Almeida

  * **Gerente de Testes:** Ana Costa

  * **Analista de Qualidade:** Felipe Santos

## 7. **Os Riscos Associados aos Testes Descrição:**

Os riscos são possíveis problemas que podem impactar a execução dos testes ou o sucesso do produto.

### **Exemplo para o App de Delivery:**

* **Falta de Integração com APIs Externas:** Se os serviços de pagamento ou rastreamento de pedidos não estiverem disponíveis no ambiente de testes, pode haver atrasos na execução.

  * **Problemas de Conectividade:** Testes dependem de uma boa conectividade com a internet, e qualquer falha pode comprometer a simulação de cenários reais de uso.

  * **Alocação Insuficiente de Recursos:** Caso a equipe de teste não seja suficiente para cobrir todos os cenários até o prazo final, pode ocorrer falta de cobertura nos testes.

## **Especificação dos Casos de Teste**

### 1. **Caracterização do Caso de Teste Descrição:**

Cada caso de teste descreve uma situação ou funcionalidade específica do aplicativo que precisa ser verificada. É uma maneira de validar se o sistema está funcionando conforme esperado.

### **Exemplo para o App de Delivery:**

| Identificador | CT-01 |
| :---- | :---- |
| **Caso de Teste** | Finalizar pedido com aplicação de cupom de desconto |
| **Descrição** | Verificar se o cupom de desconto é aplicado corretamente no total do pedido durante o checkout. |
| **Entradas** | Cupom válido: "DESCONTO10" Valor do pedido: R$100,00 |
| **Resultados Esperados** | Com o cupom "DESCONTO10", o total do pedido deve ser reduzido para R$90,00. Se um cupom inválido for inserido, uma mensagem de erro deve ser exibida. |
| **Critérios para Aprovação/Rejeição** | Aprovação: O desconto é aplicado corretamente e o total do pedido está correto. Rejeição: O sistema não aplica o desconto ou exibe mensagens de erro inadequadas. |
| **Recursos para o Caso de Teste** | Ambiente de Teste: Banco de dados com pedidos e cupons cadastrados. Ferramentas: Selenium para automação do teste. |
| **Restrições de Uso** | O cupom de desconto deve ser aplicado apenas em pedidos acima de R$50,00. O cupom deve estar ativo e dentro da validade. |
| **Dependências** | \- O caso de teste "Finalizar pedido com cupom de desconto" depende do caso de teste "Adicionar itens ao carrinho". |
| **Observações Adicionais** | Realizar testes com diferentes cupons e valores de pedido para garantir a cobertura. Documentar quaisquer anomalias ou comportamentos inesperados. |

### 2. **Especificação de Entradas, Resultados Esperados e Casos de Testes Descrição:**

Nesta seção, devem ser descritas as entradas que o sistema deve receber e os resultados esperados ao processar essas entradas. Técnicas como **particionamento por classes de equivalência** ou **grafo de causa e efeito** devem ser aplicadas aqui.

**Exemplo:**

| Condição de Entrada | Classes Válidas | Classes Inválidas |
| :---- | :---- | ----- |
| **Cupom de Desconto** | "DESCONTO10" "FRETEGRATIS" | "DESCONTO15" "INVALIDO" Vazio |
| **Valor do Pedido** | \- R$50,01 e acima | \- R$50,00 e abaixo |
| **Status do Cupom** | \- Ativo | Expirado Inativo |
