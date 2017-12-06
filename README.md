# Dotnet - guia de linhas de comando

linhas de comando úteis para trabalhar com .Net Core via terminal

> Criar um Solução

`dotnet new sln --name <nome-solução>`

Esta linha de comando irá criar uma solução com o nome especificado.

> Criar um projeto de referência

`dotnet new classlib --name <nome-projeto>`

Esta linha de comando irá criar uma pasta com o nome do projeto especificado e dentro da pasta um arquivo `.csproj` com o nome especificado.

> Criar um projeto do tipo Console

`dotnet new console --name <nome-projeto>`

Esta linha de comando irá criar uma pasta com o nome do projeto especificado e dentro da pasta um arquivo `.csproj` com o nome especificado.

> Criar um projeto de páginas Razor

`dotnet new razor --name <nome-projeto>`

Esta linha de comando irá criar uma pasta com o nome do projeto especificado e dentro da pasta um arquivo `.csproj` com o nome especificado.

> Adicionar um projeto à solução do diretório atual

`dotnet sln add <nome-projeto>\<nome-projeto>.csproj`

> Adicionar uma referencia nuget package ao projeto

`dotnet add package <nome-pacote>`

esta linha de comando deve ser executada no diretório do projeto na qual deseja adicionar o package

> Adicionar referencia de um projeto para outro projeto

`dotnet add reference ..\<nome-projeto>\<nome-projeto>.csproj`

O Comando deve ser executado no diretório do projeto que será adicionada a referencia.



