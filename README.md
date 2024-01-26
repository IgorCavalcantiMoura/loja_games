![Loja de Games](https://github.com/IgorCavalcantiMoura/loja_games/blob/main/midia/Proj%20Loja%20de%20Games.png)



# Backend para Loja de Games 🎮🕹️
![Static Badge](https://img.shields.io/badge/EM%20DESENVOLVIMENTO%20-%20PROJETO%20EM%20ANDAMENTO)

Este projeto consiste na implementação do backend para uma loja de games, proporcionando a manipulação eficiente dos dados dos produtos da loja. Os produtos estão organizados por categorias, permitindo uma gestão simplificada e intuitiva.

## Tecnologias Utilizadas

- Spring Framework: O projeto foi desenvolvido utilizando o Spring Framework, seguindo as melhores práticas recomendadas para garantir uma arquitetura robusta e escalável.
- Spring Security: A camada de segurnaça foi desenvolvida utilizando o Spring Security, fornece suporte para autenticação por meio de diferentes métodos, como login com nome de usuário e senha, autenticação baseada em token, autenticação com certificados, etc.
- Banco de Dados: A aplicação utiliza o MySQL para armazenar e gerenciar as informações dos produtos e categorias. A configuração do banco de dados pode ser encontrada no arquivo application.properties.

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

### CRUD de Usuário

- Cadastrar Usuário: Endpoint para cadastrar um novo usuário Admin. na loja.

- Buscar Usuário por ID: Recurso para obter as informações de um Usuário específico com base no seu ID.

- Listar Todas os Usuários: Endpoint para listar todas os Usuários disponíveis na loja.

- Atualizar Usuário: Permite a atualização dos dados de um usuário existente na loja.

- Listar Produtos por Usuário: Recurso que lista todos os produtos pertencentes a um usuário específico.

## Relacionamento One to Many

As classes Categoria e Produto possuem um relacionamento do tipo One to Many, garantindo que uma categoria pode conter vários produtos.

## Boas Práticas

O projeto segue as boas práticas de desenvolvimento Spring, adotando uma estrutura de código organizada e modular, incluindo o uso de Model, Repository e Controller para manter a coesão e a clareza do código.

## Testes

A API foi testada utilizando o Insomnia, garantindo que todas as funcionalidades foram implementadas corretamente e que a aplicação responde de acordo com as especificações.

Observação: Certifique-se de ter o ambiente configurado corretamente e o banco de dados inicializado antes de testar a API.
## Como Executar o Projeto

    Clone o repositório.
    Configure o banco de dados no arquivo application.properties.
    Execute a aplicação Spring Boot.
    Utilize o Insomnia para testar a API.

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/igor-cavalcanti-moura/)
