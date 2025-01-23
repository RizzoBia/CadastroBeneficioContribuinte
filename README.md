<h1>
   Cadastro de Benefícios e Contribuintes
</h1>

Repositório desenvolvido para fins de demonstração de conhecimento.

## Objetivo
Desenvolver um Sistema de Gestão de Benefícios e Contribuintes, onde seja possível:

1) Cadastrar os Benefícios e Descontos

   1.1) Editar os Benefícios e Descontos

   1.2) Ao excluir um benefício, deverá ser removido qualquer vínculo com o CNPJ anteriormente vinculado

2) Cadastrar Contribuintes

   2.1) Editar os Contribuintes cadastrados

   2.2) Ao excluir um CNPJ, deverá ser removido qualquer vínculo com o benefício anteriormente vinculado
   
## Ferramentas
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-boostrap-0D1117?style=for-the-badge&logo=bootstrap&labelColor=0D1117)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000?style=for-the-badge&logo=postgresql)
![Windows](https://img.shields.io/badge/Windows-000?style=for-the-badge&logo=windows&logoColor=2CA5E0)


## Funcionalidades
<table>
  <tbody align="left">
    <tr>
      <td>01</td>
      <td>Gerenciamento de Benefícios (CRUD)</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Gerenciamento de Contribuintes (CRUD)</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Vinculação entre Benefícios e Contribuintes</td>  
    </tr>
    <tr>
      <td>04</td>
      <td>Visualização de Dados Consolidados</td>    
    </tr>
  </tbody>
</table>

---
## Percurso
1) Estrutura Inicial do Banco de Dados no PostgreSQL

   1.1) Criar as Tabelas "Benefícios" e "Contribuintes" mantendo o id como chave primária (Script está nos arquivos)

   1.2) Popular as tabelas com dados fictícios gerados por IA 

---
## Consultas Realizadas
[Tutorial: Implementar a funcionalidade CRUD – ASP.NET MVC com EF Core](https://learn.microsoft.com/pt-br/aspnet/core/data/ef-mvc/crud?view=aspnetcore-9.0)

[ASP.NET Core MVC CRUD Operations with Product Example](https://medium.com/@ravipatel.it/asp-net-core-mvc-crud-operations-with-product-example-for-absolute-beginners-in-net-8-b012700c8cf6)

[Work with .resx files programmatically](https://learn.microsoft.com/en-us/dotnet/core/extensions/work-with-resx-files-programmatically)

[Using .Resx files for global application messages?](https://stackoverflow.com/questions/1820912/using-resx-files-for-global-application-messages)

[Want to learn and master C#?](https://exercism.org/tracks/csharp)

[C#:criando sua primeira aplicação](https://cursos.alura.com.br/course/csharp-criando-primeira-aplicacao)
