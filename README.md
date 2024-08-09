# Projeto - Login com cadastro

# Descrição do Projeto
Este projeto possui duas páginas HTML básicas:

* login.html: Um formulário de login.
* users.html: Um formulário para adicionar nomes e uma tabela para exibi-los.
# Estrutura do Projeto
* login.html: Contém um formulário com campos para e-mail e senha, e um botão de acessar.
* users.html: Contém um campo para inserir um nome, um botão para salvar o nome, e uma tabela para listar os nomes dos usuários.
# Arquivos CSS
* main.css: Estilos para formulários e tabelas.
# Arquivos JavaScript
* main.js: Scripts gerais para ambas as páginas.
* controller.js: Scripts específicos para o formulário de login (somente em login.html).
# Funcionalidades
1. Validação de Acesso
A função acessar() valida se os campos de e-mail e senha foram preenchidos. Se algum campo estiver vazio, exibe um alerta pedindo para preencher todos os campos. Caso contrário, redireciona o usuário para cadastro.html.

2. Armazenamento de Nomes
A função salvarUser() adiciona um nome à lista dadosLista e atualiza a tabela HTML com os nomes. Se o campo de nome estiver vazio, exibe um alerta pedindo para informar um nome para cadastro.

3. Criação e Gerenciamento de Lista
* Criação de Lista: A função criaLista() gera a tabela HTML com os nomes armazenados. Cada linha da tabela possui botões para editar ou excluir o nome correspondente.
Edição de Nomes: A função editar(i) preenche o campo de entrada com o nome selecionado para edição e remove o nome da lista.
* Exclusão de Nomes: A função excluir(i) remove o nome da lista e da tabela HTML.
# Requisitos
* Um ambiente de desenvolvimento web com suporte a HTML e JavaScript.
* Navegador web para executar e testar o código.
# Como Usar
* Validação de Acesso: Insira um e-mail e uma senha nos campos correspondentes e clique no botão de acesso. Se os campos estiverem preenchidos, você será redirecionado para a página de cadastro.

# Armazenamento e Gerenciamento de Nomes:

Preencha o campo de nome e clique no botão para salvar. O nome será adicionado à lista e exibido na tabela.
Para editar um nome, clique no botão "Editar" na linha correspondente. O nome será preenchido no campo de entrada para edição.
Para excluir um nome, clique no botão "Excluir" na linha correspondente. O nome será removido da lista e da tabela.