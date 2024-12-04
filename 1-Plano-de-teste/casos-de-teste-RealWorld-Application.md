#Relatório de Testes: RealWorld Application
Objetivo do Teste: Verificar a funcionalidade e usabilidade do sistema em cenários reais, validando comportamentos esperados de acordo com os requisitos de software.




#Caso de Teste 1: Cadastro de Novo Usuário
Objetivo: Verificar se o sistema permite cadastrar um novo usuário com dados válidos.
Entradas:
   Nome de usuário: "NovoUsuario"
   E-mail: "novo@email.com"
   Senha: "senha123"
   Procedimentos:
Acessar a página de cadastro:
   Preencher os campos de nome, e-mail e senha.
   Clicar no botão "Sign Up".
Saída Esperada:
   Redirecionamento automático para o feed do usuário.
   Nome de usuário exibido no menu de navegação superior.
   Mensagem de boas-vindas ou acesso ao feed pessoal.
Observações: Testar também cenários de erro, como tentativas de cadastro com e-mails já existentes ou senha inválida.




#Caso de Teste 2: Editar Perfil do Usuário
Objetivo: Validar a funcionalidade de edição de perfil e atualização dos dados.
Entradas:
Nome de usuário: "UsuarioEditado"
Biografia: "Eu sou um tester!"
Nova foto de perfil: URL de uma imagem válida.
Procedimentos:
Acessar a página de configurações:
   Alterar os campos Nome de Usuário, Biografia e Foto de Perfil.
   Salvar as alterações.
Saída Esperada:
   Dados atualizados são exibidos no perfil público do usuário.
   Nova foto de perfil aparece no cabeçalho de navegação.
   Mensagem de sucesso: "Profile updated successfully."




#Caso de Teste 3: Curtir um Artigo
Objetivo: Verificar a funcionalidade de curtir artigos e a atualização do contador de likes.
Entradas:
Artigo existente no feed global.
Procedimentos:
   Acessar o feed global.
   Localizar um artigo e clicar no ícone de "coração" para curtir.
   Atualizar a página. 
Saída Esperada:
   O contador de likes do artigo aumenta em +1.
   Ícone de "coração" permanece ativo após a atualização da página.
   O mesmo comportamento é esperado em diferentes dispositivos (responsividade).



   
#Caso de Teste 4: Salvar Artigo como Favorito
Objetivo: Validar a funcionalidade de salvar artigos na lista de favoritos do usuário.
Entradas:
Artigo existente no feed global.
Procedimentos:
   Acessar o feed global.
   Clicar no botão "Favoritar" de um artigo.
   Navegar para o perfil do usuário e acessar a aba "Favoritos".
Saída Esperada:
   O artigo aparece listado na aba "Favoritos" do usuário.
   Após desfavoritar, o artigo é removido da aba "Favoritos".
   Caso de Teste 5: Visualizar Perfil de Outro Usuário

   
#Objetivo: Garantir que o perfil de outros usuários exiba as informações públicas corretamente.
Entradas:
Nome de um usuário existente no feed global.
Procedimentos:
   Acessar o feed global.
   Clicar no nome ou avatar de um autor de artigo.
   Verificar as informações do perfil do usuário (artigos, biografia, etc.).
Saída Esperada:
   Exibição dos artigos criados pelo usuário.
   Biografia e imagem de perfil são exibidas corretamente.
   A opção "Seguir" aparece para o visitante.
   Caso de Teste 6: Seguir/Deixar de Seguir Usuário


#Objetivo: Testar a funcionalidade de seguir e deixar de seguir outros usuários.
Entradas:
Perfil de um usuário existente.
Procedimentos:
   Acessar o perfil de outro usuário.
   Clicar no botão "Follow" para segui-lo.
   Atualizar a página e verificar a persistência do estado.
   Clicar em "Unfollow" e repetir a verificação.
Saída Esperada:
   Após seguir, o botão muda para "Unfollow".
   O contador de seguidores do perfil é atualizado corretamente.
   Após deixar de seguir, o botão retorna ao estado "Follow".
