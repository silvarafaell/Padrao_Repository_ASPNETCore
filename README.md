Curso Padrão Repository com ASP.NET Core no nextwave(LuisDEV) 
 - Aprenda Padrão Repository com ASP.NET Core

### Padrão Repository
 - Padrão utilizado para abstrair o acesso a dados, permitindo a abstração dos detalhes de implementação.
   - Ao se utilizar também uma interface, é também realizado o desacoplamneto
 - Componente de domínio do Domain-Driven Design, responsável pelo o acesso aos objetos armazenados, mas sem especificar a respeito de sua fonte.
 - Com o seu uso, classes da camada Application como serviços de aplicação ou commands/queries não precisam mais ter dependência em bibliotecas de acesso a dados como Entity Framework Core e Dapper.
 - Na arquitetura Limpa, é composto por:
   - Interface: contém o contrato dos métodos do repositório, ficando localizada na camada Core.
   - Implementação: contém a implementação dos métodos definidos na interface, podendo utilizar Entity Framework Core, Dapper, ADO.NET, ou outras ferramentas de acesso a dados.
