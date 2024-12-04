# **Casos de Testes Aplicados no Cypress**

**Objetivo do Teste:**  
O sistema testado é uma plataforma web construída em Node e React que permite aos usuários realizar login, publicar artigos, adicionar comentários e excluir interações. Para validar sua funcionalidade, utilizamos o Cypress para realizar Testes de Sistema, simulando interações reais do usuário e verificando a integração entre as diferentes partes do sistema.

---

## Classificação dos Testes

Os testes realizados são **Testes de Sistema**, que verificam a funcionalidade completa do software a partir da perspectiva do usuário final. Esse tipo de teste é essencial para validar a integração das funcionalidades e a experiência geral do sistema.

---

## Funcionalidades Testadas

Para esta apresentação, escolhemos testar 4 funcionalidades principais:
1. **Login**
2. **Publicação de Artigos**
3. **Adição de Comentários**
4. **Exclusão de Comentários**

---

### Caso de Teste 1: Login

**Objetivo:**  
Verificar o processo de autenticação ao inserir credenciais válidas.

**Procedimentos:**
1. Inserir as credenciais de login válidas.
2. Clicar no botão "Login".
3. Verificar se o sistema redireciona para o feed principal com a classe "Your Feed" ativa.

**Saída Esperada:**
- O sistema deve redirecionar para o feed principal.
- A classe "Your Feed" deve estar ativa, indicando sucesso no login.

---

### Caso de Teste 2: Publicação de Artigos

**Objetivo:**  
Validar a funcionalidade de publicação de artigos preenchendo título, descrição, conteúdo e tags.

**Procedimentos:**
1. Preencher os campos de título, descrição, conteúdo e tags.
2. Clicar no botão "Publicar".
3. Verificar se o artigo aparece corretamente no feed.

**Saída Esperada:**
- O artigo publicado deve aparecer no feed com o título exibido corretamente.

---

### Caso de Teste 3: Adicionar Comentário

**Objetivo:**  
Validar a funcionalidade de adição de comentários em artigos existentes.

**Procedimentos:**
1. Selecionar um artigo existente.
2. Adicionar um comentário no campo destinado a comentários.
3. Publicar o comentário.

**Saída Esperada:**
- O comentário deve aparecer na interface do artigo, indicando que foi adicionado com sucesso.

---

### Caso de Teste 4: Exclusão de Comentário

**Objetivo:**  
Validar a funcionalidade de exclusão de comentários previamente adicionados.

**Procedimentos:**
1. Selecionar um comentário existente.
2. Clicar no ícone de excluir para remover o comentário.
3. Verificar que o comentário foi removido da interface.

**Saída Esperada:**
- O comentário não deve aparecer mais na lista de interações do artigo.

---

## Resultados e Conclusão

Os testes demonstraram que o sistema responde corretamente às interações do usuário nas funcionalidades avaliadas, indicando que elas estão integradas e funcionando como esperado.

Se este fosse um cenário real de teste, seria essencial realizar uma cobertura completa de todas as funcionalidades para garantir a robustez do sistema em diferentes cenários. Contudo, a seleção das funcionalidades testadas foi suficiente para demonstrar a eficácia do Cypress e validar o funcionamento de partes críticas do sistema.
