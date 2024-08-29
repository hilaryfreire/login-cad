
## Projeto de Cadastro e Login
Este projeto é uma aplicação intuitiva para gerenciamento de usuários, oferecendo funcionalidades essenciais de login, cadastro e edição de registros. O sistema é composto por duas telas principais: a tela de login e a tela de cadastro. 
 
## Campos: Email e Senha
* Validação
* Descrição: O sistema verifica se ambos os campos, "Email" e "Senha", foram preenchidos antes de permitir o acesso.
Comportamento:
* Campo Vazio: Se qualquer um dos campos estiver vazio, é exibido um alerta solicitando que o usuário preencha todos os campos obrigatórios.
* Formato do Email: O email inserido é validado quanto ao formato correto (por exemplo, "usuario@dominio.com").
* Segurança da Senha: Verifica se a senha atende aos critérios de segurança, como comprimento mínimo e complexidade, se aplicável.
 
## Campos: Nome do Usuário
* Ações Disponíveis:
Salvar Usuário

* Descrição: Adiciona o nome do usuário ao array dadosLista e atualiza a tabela de usuários exibida na interface.
Funcionamento:
* Adição: O nome inserido no campo de entrada é adicionado à lista de usuários.
* Atualização: A tabela de usuários é atualizada para refletir a nova adição, garantindo que o nome do usuário apareça na lista.
Editar Usuário

* Descrição: Permite modificar o nome de um usuário selecionado da lista.
Funcionamento:
* Seleção: O usuário seleciona um nome existente na tabela.
* Edição: O nome selecionado é removido da lista dadosLista e exibido no campo de entrada para edição.
* Atualização: Após a edição, o nome atualizado é reinserido na lista e a tabela de usuários é atualizada para refletir a alteração.
Excluir Usuário

* Descrição: Remove o nome de um usuário da lista e da tabela.
Funcionamento:
* Seleção: O usuário seleciona um nome na tabela que deseja excluir.
* Remoção: O nome selecionado é removido do array dadosLista e a tabela é atualizada para refletir a exclusão, garantindo que o nome do usuário seja removido da exibição.

## Uso
Acesse o index.html para iniciar o login.
Preencha os campos de email e senha e clique no botão de acesso.
Na tela de cadastro, insira o nome do usuário e clique em "Salvar Usuário" para adicionar o nome à lista.
Edite ou exclua nomes da lista usando os botões apropriados.
 
## Observações
Certifique-se de que os IDs dos elementos HTML correspondam aos usados no JavaScript.
A tabela de usuários é atualizada dinamicamente toda vez que um nome é adicionado, editado ou excluído.
 
 
## Fontes consultadas
 
https://developer.mozilla.org/en-US/docs/Web/API/HTMLTableElement/deleteRow
 
https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
 