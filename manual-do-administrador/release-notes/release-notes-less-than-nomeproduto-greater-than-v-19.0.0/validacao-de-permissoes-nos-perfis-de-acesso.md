# Validação de Permissões nos Perfis de Acesso

O sistema agora valida as permissões definidas nos perfis de acesso, garantindo maior controle sobre as ações dos administradores. Principais funcionalidades:

* **Visualização Restrita**: Se a permissão de visualização de perfis de acesso estiver desativada, os submenus e telas relacionadas a perfis de acesso não serão exibidos ou acessíveis.
* **Cadastro Bloqueado**: Sem a permissão de cadastro, o submenu "Cadastrar Novo Perfil de Acesso" e o botão "Novo Perfil" não estarão disponíveis.
* **Edição Limitada**: Usuários sem permissão para editar perfis não poderão acessar a funcionalidade de edição.
* **Proibição de Exclusão**: A exclusão de perfis estará indisponível se a permissão correspondente estiver desativada.
* **Proteção para Último Administrador**: Não será possível remover ou alterar um perfil vinculado ao último administrador com todas as permissões, garantindo a continuidade da gestão.

Essas validações reforçam a segurança e o controle sobre as ações administrativas no sistema.

