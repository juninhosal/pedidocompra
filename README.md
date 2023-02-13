# pedidocompra
Sistema para pedido de compra

# manyminds
Teste da empresa ManyMinds

Aplicativo Teste
Desenvolver um projeto em Codeigniter 3 (Versão utilizada pela equipe de
desenvolvimento) com o banco de dados MariaDB, não devem ser utilizados recursos
como "Migrations" e nenhum tipo de ORM para gerar os scripts prontos, os scripts
devem ser desenvolvidos manualmente. Pode ser utilizado JQuery ou JS puro como
linguagem FRONT-END. O projeto será avaliado de acordo com sua complexidade,
otimização, conhecimento, segurança, criatividade e etc. Tente demonstrar todo o seu
conhecimento nesse projeto, os requisitos devem ser cumpridos, mas o candidato tem
autonômia de adicionar qualquer recurso, cadastro ou funcionalidade que possa
demonstrar ainda mais seu conhecimento.
Recomendamos que a entrega do projeto seja feita por meio do GIT.
O projeto deve conter os seguintes elementos:
- Sistema de login:
- Caso não haja nenhuma forma de cadastrar um usuário de acesso ao portal
diretamente no Login, favor informar o usuário e senha para ser possível avaliar o
projeto
- [Desafio] Criar trava de endereço de IP por um determinado período de tempo caso o
usuário erre a senha 3 vezes seguidas em um mesmo local
- CRUD de colaborador
- Os campos podem ser definidos pelo próprio candidato, mínimo de 7 campos no
banco
- O colaborador pode ser um usuário com acesso ao portal ou um fornecedor
- O colaborador somente pode ser inativado, não deletado, podendo ser reativado
posteriormente. Quando inativo, não permitir alterações
- [Desafio] Desenvolvimento de sistema básico de permissão de tela para
colaboradores com acesso ao portal
- [Opcional] O colaborador pode ter quantos endereços desejar:
- O endereço deve ser composto por uma série de informações que podem ser
determinadas pelo candidato (Como CEP, cidade, estado, rua...)
- CRUD de produtos:
- Os campos podem ser definidos pelo próprio candidato, mínimo de 3 campos no
banco
- O produto somente pode ser inativado, não deletado, podendo ser reativado
posteriormente. Quando inativo, não permitir alterações
- CRUD de pedidos de compra:
- Deve ser selecionado um fornecedor ativo
- Deve haver um campo para observações
- O pedido pode ter 2 status, sendo eles "ativo" ou "finalizado". Quando "ativo" o
pedido pode ser alterado e deletado, quando "finalizado" não permitir alterações ou
exclusões
- O pedido deve conter ao menos 1 item (linha)
- Criar forma de adicionar/alterar/deletar os itens (linhas) do pedido:
- Deve ser selecionado um produto ativo no item
- Deve ser adicionada a quantidade
- Deve ser adicionado o preço unitário
- [Opcional] Desenvolvimento de sistema e listagem de logs de alterações do sistema.
- [Desafio] Criar WS de retorno de pedidos finalizados:
- Deve ser retornado em formato JSON todas as informações de cada pedido e seus
itens, as informações do usuário que criou o documento, do fornecedor e dos
produtos de cada linha do pedido.
- Criar método de autenticação para consumo do WS
- Outros end-points e funcionamento do WS podem ser definidos pelo candidato

