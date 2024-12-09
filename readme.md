# Trabalho Prático et III - Teste de Sistema com Cypress


#### Disciplina: Teste, Verificação e Validação de Software  
#### Docente: Andrey Rodrigues  
#### Discentes: Illgner Anderson, João Victor Vasconcelos, Victor Gabriel Araújo e Victor Queiroz Barbosa  

---

Este repositório tem como objetivo documentar a **Etapa III** do trabalho prático da disciplina Teste, Verificação e Validação de Software.  

O trabalho consiste na elaboração e execução de **testes de sistema**, focados em verificar as funcionalidades da aplicação e garantir que as partes do sistema funcionem de forma integrada. Além disso, os testes simulam cenários reais de uso, contribuindo para a validação da aplicação do ponto de vista do usuário final.  

A ferramenta **Cypress** foi escolhida para a execução dos testes devido à sua facilidade de integração, suporte a testes automatizados end-to-end e sua capacidade de simular o comportamento do usuário na interface.  

A aplicação usada nos testes é o **Conduit**, um exemplo de aplicação de blog open-source desenvolvida em **Node.js** e **React**, com funcionalidades como autenticação de usuários, criação de artigos, comentários e interações sociais.  

---

## 1. Simulação de Casos de Teste  

Para os testes, escolhemos **quatro funcionalidades principais** do sistema. A seleção foi feita de forma estratégica, considerando sua relevância para demonstrar o funcionamento do sistema. Contudo, ressaltamos que, em um ambiente real, todas as funcionalidades deveriam ser testadas, incluindo cenários de erro e validações em bordas.  

Os testes implementados foram:  
1. **Login de Usuário:** Verificar o processo de autenticação e acesso ao feed pessoal.  
2. **Publicação de Artigo:** Testar a criação e publicação de um novo artigo.  
3. **Comentário em Artigo:** Simular a adição de um comentário a um artigo existente.  
4. **Exclusão de Comentário:** Validar a funcionalidade de remover um comentário previamente adicionado.  

Além desses, identificamos outros **seis casos de teste relevantes**, documentados no relatório, com base em entradas, saídas esperadas e passos para sua execução.  

---

## 2. Demonstração Prática  

Os testes foram executados com sucesso no **Cypress**, validando os seguintes comportamentos:  
- O sistema autentica usuários registrados, redirecionando-os ao feed pessoal.  
- Usuários conseguem criar, publicar e visualizar artigos em tempo real.  
- Comentários podem ser adicionados e excluídos, com as atualizações refletidas imediatamente na interface.  

A demonstração em sala irá simular esses testes, apresentando o comportamento esperado e destacando como os casos de teste foram elaborados para cobrir diferentes aspectos do sistema.  

---

## Tecnologias Utilizadas  

- **Node.js** e **React:** Linguagens usadas no desenvolvimento da aplicação.  
- **Cypress:** Ferramenta utilizada para testes automatizados de sistema, com suporte a validação de interações complexas na interface de usuário.  

---

