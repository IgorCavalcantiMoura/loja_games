
# Backend para Loja de Games

Este projeto consiste na implementação do backend para uma loja de games, proporcionando a manipulação eficiente dos dados dos produtos da loja. Os produtos estão organizados por categorias, permitindo uma gestão simplificada e intuitiva.

## Tecnologias Utilizadas

- Spring Framework: O projeto foi desenvolvido utilizando o Spring Framework, seguindo as melhores práticas recomendadas para garantir uma arquitetura robusta e escalável.

- Banco de Dados: A aplicação utiliza um banco de dados para armazenar e gerenciar as informações dos produtos e categorias. A configuração do banco de dados pode ser encontrada no arquivo application.properties.

## Funcionalidades Implementadas
### CRUD de Produto

- Criar Produto: Endpoint para cadastrar um novo produto na loja.

- Buscar Produto por ID: Recurso para obter as informações de um produto específico com base no seu ID.

- Listar Todos os Produtos: Endpoint para listar todos os produtos disponíveis na loja.

- Atualizar Produto: Permite a atualização dos dados de um produto existente na loja.

- Remover Produto: Endpoint para excluir um produto do sistema.

- Buscar Produtos por Categoria: Recurso que lista todos os produtos de uma categoria específica.

### CRUD de Categoria

- Criar Categoria: Endpoint para cadastrar uma nova categoria na loja.

- Buscar Categoria por ID: Recurso para obter as informações de uma categoria específica com base no seu ID.

- Listar Todas as Categorias: Endpoint para listar todas as categorias disponíveis na loja.

- Atualizar Categoria: Permite a atualização dos dados de uma categoria existente na loja.

- Remover Categoria: Endpoint para excluir uma categoria do sistema.

- Listar Produtos por Categoria: Recurso que lista todos os produtos pertencentes a uma categoria específica.

## Relacionamento One to Many

As classes Categoria e Produto possuem um relacionamento do tipo One to Many, garantindo que uma categoria pode conter vários produtos.
Boas Práticas

O projeto segue as boas práticas de desenvolvimento Spring, adotando uma estrutura de código organizada e modular, incluindo o uso de Model, Repository e Controller para manter a coesão e a clareza do código.
Testes

A API foi testada utilizando o Insomnia, garantindo que todas as funcionalidades foram implementadas corretamente e que a aplicação responde de acordo com as especificações.

Observação: Certifique-se de ter o ambiente configurado corretamente e o banco de dados inicializado antes de testar a API.
## Como Executar o Projeto

    Clone o repositório.
    Configure o banco de dados no arquivo application.properties.
    Execute a aplicação Spring Boot.
    Utilize o Insomnia para testar a API.