O sistema testado é uma plataforma web construída em node e react que permite aos usuários realizar login, publicar artigos, adicionar comentários e excluir interações. Para validar sua funcionalidade, utilizamos o Cypress para realizar Testes de Sistema, simulando interações reais do usuário e verificando a integração entre as diferentes partes do sistema.
Classificação dos Testes
Os testes realizados são Testes de Sistema, que verificam a funcionalidade completa do software a partir da perspectiva do usuário final. Esse tipo de teste é essencial para validar a integração das funcionalidades e a experiência geral do sistema.
Funcionalidades Testadas
Para esta apresentação, escolhemos testar 4 funcionalidades principais.
 login, publicação de artigos, adição de comentários e exclusão de comentários. 
1. Login
O teste verificou o processo de autenticação ao inserir credenciais válidas. Após o login, o sistema deve redirecionar para o feed principal, com a class "Your Feed" ativo, indicando sucesso.
2. Publicação de Artigos
Simulamos a criação de um artigo preenchendo título, descrição, conteúdo e tags. Após publicar, verificamos a exibição do artigo na tela e a geração correta de seu título no feed.
3. Adicionar Comentário
A funcionalidade foi validada simulando a inserção de um comentário em um artigo existente. Após a postagem, confirmamos sua presença na interface.
4. Exclusão de Comentário
Esse teste validou a remoção de comentários. Considerando que o comentário foi previamente criado, realizamos sua exclusão e verificamos que ele não aparece mais na lista de interações.
Resultados e Conclusão
Os testes demonstraram que o sistema responde corretamente às interações do usuário nas funcionalidades avaliadas, indicando que elas estão integradas e funcionando como esperado.
Se este fosse um cenário real de teste, seria essencial realizar uma cobertura completa de todas as funcionalidades para garantir a robustez do sistema em diferentes cenários. Contudo, a seleção das funcionalidades testadas foi suficiente para demonstrar a eficácia do Cypress e validar o funcionamento de partes críticas do sistema.
