Relatório de Testes: RealWorld Application
Objetivo do Teste: Verificar a funcionalidade e usabilidade do sistema em cenários reais, validando comportamentos esperados de acordo com os requisitos de software.



Relatório de Teste 1: Login com Credenciais Válidas
Objetivo: Verificar se o usuário pode realizar login com credenciais válidas.

Pré-condição: O usuário já possui uma conta registrada.

Passos:

Navegar para a página de login.

Inserir o e-mail válido.

Inserir a senha válida.

Clicar no botão de login.

Resultado Esperado: O usuário é redirecionado para a página inicial.

Resultado Obtido: Conforme o esperado. O usuário foi redirecionado para a página inicial.

Relatório de Teste 2: Login com Credenciais Inválidas
Objetivo: Verificar se o sistema trata corretamente tentativas de login com credenciais inválidas.

Pré-condição: O usuário tenta fazer login com e-mail ou senha inválidos.

Passos:

Navegar para a página de login.

Inserir o e-mail inválido.

Inserir a senha inválida.

Clicar no botão de login.

Resultado Esperado: O sistema exibe uma mensagem de erro indicando que as credenciais são inválidas.

Resultado Obtido: Conforme o esperado. Mensagem de erro exibida.

Relatório de Teste 3: Logout
Objetivo: Verificar se o usuário pode realizar logout do sistema.

Pré-condição: O usuário está logado no sistema.

Passos:

Clicar no botão de logout.

Resultado Esperado: O usuário é redirecionado para a página de login.

Resultado Obtido: Conforme o esperado. O usuário foi redirecionado para a página de login.

Relatório de Teste 4: Publicação de Artigos
Objetivo: Verificar se o usuário pode publicar um artigo.

Pré-condição: O usuário está logado no sistema.

Passos:

Navegar para a página de publicação de artigos.

Inserir um título para o artigo.

Inserir o conteúdo do artigo.

Clicar no botão de publicar.

Resultado Esperado: O artigo é publicado e exibido na lista de artigos.

Resultado Obtido: Conforme o esperado. O artigo foi publicado e exibido na lista de artigos.

Relatório de Teste 5: Validação de Campos de Publicação de Artigos
Objetivo: Verificar se os campos obrigatórios estão sendo validados.

Pré-condição: O usuário está tentando publicar um artigo.

Passos:

Navegar para a página de publicação de artigos.

Inserir o conteúdo do artigo sem título.

Clicar no botão de publicar.

Resultado Esperado: O sistema exibe uma mensagem de erro indicando que o título é obrigatório.

Resultado Obtido: Conforme o esperado. Mensagem de erro exibida.

Relatório de Teste 6: Edição de Artigos
Objetivo: Verificar se o usuário pode editar um artigo já publicado.

Pré-condição: O usuário está logado e possui um artigo publicado.

Passos:

Navegar para o artigo publicado.

Clicar no botão de editar.

Alterar o título e o conteúdo do artigo.

Salvar as alterações.

Resultado Esperado: As alterações são exibidas no artigo.

Resultado Obtido: Conforme o esperado. Alterações exibidas no artigo.

Relatório de Teste 7: Exclusão de Artigos
Objetivo: Verificar se o usuário pode excluir um artigo.

Pré-condição: O usuário está logado e possui um artigo publicado.

Passos:

Navegar para o artigo publicado.

Clicar no botão de excluir.

Resultado Esperado: O artigo é removido da lista de artigos.

Resultado Obtido: Conforme o esperado. Artigo removido.

Relatório de Teste 8: Adição de Comentários
Objetivo: Verificar se o usuário pode adicionar comentários em um artigo.

Pré-condição: O usuário está logado e visualiza um artigo.

Passos:

Inserir comentário no campo de comentários.

Clicar no botão de adicionar comentário.

Resultado Esperado: O comentário é exibido abaixo do artigo.

Resultado Obtido: Conforme o esperado. Comentário exibido abaixo do artigo.

Relatório de Teste 9: Exclusão de Comentários
Objetivo: Verificar se o usuário pode excluir um comentário que adicionou.

Pré-condição: O usuário está logado e possui um comentário publicado.

Passos:

Navegar para o comentário.

Clicar no botão de excluir comentário.

Resultado Esperado: O comentário é removido.

Resultado Obtido: Conforme o esperado. Comentário removido.

Relatório de Teste 10: Validação de Campos de Comentários
Objetivo: Verificar se o campo de comentário está sendo validado.

Pré-condição: O usuário está tentando adicionar um comentário.

Passos:

Inserir um comentário vazio.

Clicar no botão de adicionar comentário.

Resultado Esperado: O sistema exibe uma mensagem de erro indicando que o campo de comentário não pode estar vazio.

Resultado Obtido: Conforme o esperado. Mensagem de erro exibida.

Relatório de Teste 11: Visualização de Artigos
Objetivo: Verificar se o usuário pode visualizar os artigos publicados.

Pré-condição: O usuário está logado e navega pela lista de artigos.

Passos:

Navegar para a lista de artigos.

Clicar em um artigo para visualizar.

Resultado Esperado: O artigo completo é exibido.

Resultado Obtido: Conforme o esperado. Artigo completo exibido.

Relatório de Teste 12: Busca de Artigos
Objetivo: Verificar se o usuário pode buscar artigos.

Pré-condição: O usuário está logado e na página de busca.

Passos:

Inserir termo de busca.

Clicar no botão de buscar.

Resultado Esperado: A lista de artigos relevantes é exibida.

Resultado Obtido: Conforme o esperado. Lista de artigos exibida.

Relatório de Teste 13: Responsividade da Página de Login
Objetivo: Verificar se a página de login é responsiva.

Pré-condição: O usuário está na página de login.

Passos:

Redimensionar a janela do navegador para diferentes tamanhos de tela.

Resultado Esperado: A página de login ajusta-se corretamente ao tamanho da janela.

Resultado Obtido: Conforme o esperado. Página de login responsiva.

Relatório de Teste 14: Mensagens de Erro
Objetivo: Verificar se as mensagens de erro são exibidas corretamente.

Pré-condição: O usuário realiza ações incorretas, como login com senha errada ou publicação sem título.

Passos:

Tentar realizar login com senha errada.

Tentar publicar um artigo sem título.

Resultado Esperado: Mensagens de erro apropriadas são exibidas.

Resultado Obtido: Conforme o esperado. Mensagens de erro exibidas.

Relatório de Teste 15: Carregamento de Páginas
Objetivo: Verificar se as páginas carregam corretamente após ações do usuário.

Pré-condição: O usuário está logado e navega entre diferentes páginas.

Passos:

Navegar entre a página inicial, página de artigos e página de perfil.

Resultado Esperado: As páginas carregam sem erros.

Resultado Obtido: Conforme o esperado. Páginas carregadas sem erros


Esses relatórios de casos de teste cobrem as principais funcionalidades da plataforma web e validam a experiência do usuário final.
