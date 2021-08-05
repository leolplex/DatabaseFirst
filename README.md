# Npgsql Entity Framework Core Provider - DatabaseFirst



This is a workshop in order to understand the database first Entity Framework Core with PostgreSQL, you should have install postgreSQL and get a conection string and a database created. 

1. `dotnet new console -o Blogging`
2. `dotnet add package Microsoft.EntityFrameworkCore.Sqlite`
4. Install dotnet-ef
    `dotnet tool install --global dotnet-ef`
5. Install Microsoft.EntityFrameworkCore.Design
    `dotnet add package Microsoft.EntityFrameworkCore.Design`
6. Run the scaffold with connection string
    `dotnet ef dbcontext scaffold "Host=my_host;Database=my_db;Username=my_user;Password=my_pw" Npgsql.EntityFrameworkCore.PostgreSQL`
8. Run the main to test the conection and transact
