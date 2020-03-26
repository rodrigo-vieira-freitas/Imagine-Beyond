# Imagine-Beyond

# Desafio Imagine Beyond
O desafio da Imagine Beyond, gostei do desafio provou que tenho que terminar o projeto com tempo estipulado, mas com problemas com a internet, conseguir enviar o relatório, segue o código de comunicação ao banco de dados via json que é "appsettings.json". As linguagens de programação são:

- ASP.NET Core 3.1
- Sql Server 2014

Os Framework´s que foram usados são:

- Micrsosoft.AspNetCore
- Microsoft.NetCore

Os Packages:

- AutoMapper(9.0.0)
- Microsoft.EntityFrameworkCore(3.1.2)
- Microsoft.EntityFrameworkCore.SqlServer(3.0.0)
- Microsoft.EntityFrameworkCore.Tools(3.0.0)
- Microsoft.Extesions.Logging.Debug(3.0.0)
- Microsoft.VisualStudio.Web.CodeGeneration.Design(3.0.0)

# Conexão Sql Server
Ao fazer a conexão ao banco de dados via Sql Server, em vez entrar e criar tabela, fiz via Json, não precisar entrar no sql server e criar as tabelas, você cria as classes que serão os principais fornecedores que vão exibir na tela ou não como foi os campos data de criação e data de atualização nele poderia ver via sql server (neste momento eu pensei). Mas você precisa colocar o nome de Catalog como segui no exemplo logo abaixo. Segue o código que você cria em json "appsettings.json":

```sh
{   
    "ConnectionStrings": 
{     
     "DefaultConnection": "Data Source=LAPTOP-EU4I8EBK\\SQLEXPRESS;Initial Catalog=Beyond;Integrated Security=False;User ID=sa;Password=123;Connect Timeout=15;Encrypt=False;TrustServerCertificate=False"   
 },   
   "Logging": {     
       "LogLevel": {       
             "Default": "Information",       
             "Microsoft": "Warning",       
             "Microsoft.Hosting.Lifetime": "Information"     
             }   
     },   
 "AllowedHosts": "*" 
 }
```


# Conclusão:
O desafio foi muito bom, fui desafiado, não queria deixar pra lá quero terminar até o fim, mas logo eu percebi que é um CRUD simples, pensei poderia terminar em 2 horas, mas depois eu percebi que na parte de data de atualização e data de cadastro precisava implementar um código que reconheça a data do meu notebook, salvando, mesmo eu editando salvar o último dia da data. Esquecendo também utilizei validação do e-mail que foi pedido que quando for digitar com ou sem @.
