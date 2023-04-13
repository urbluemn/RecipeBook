![](https://badgen.net/badge/.Net/6.0/purple)
![](https://badgen.net/badge/EntityFramework/6.0.14/purple)
![](https://badgen.net/badge/MediatR/11.1.0/green)
![](https://badgen.net/badge/FluentValidation/11.5.1/green)
![](https://badgen.net/badge/IdentityServer4/4.1.2/green)
![](https://badgen.net/badge/AutoMapper/12.0.1/green)  

# RecipeBook
 
Simple RecipeBook WebApp consisting of three parts:  
Auth server with IdentityServer4 (https://github.com/urbluemn/RecipeBook.Identity)  
API (https://github.com/urbluemn/RecipeBook.API)  
MVC frontend project (https://github.com/urbluemn/RecipeBook.MVC)

---
If you want to install and run it on your machine, make sure you have installed MSSQL server, because both API and Auth server are using it.  
Otherwise change this parameters to be able to run the database:
Change connection strings in appsettings.json and DependencyInjection classes in both projects from SQLServer to SQLite (simply uncomment this lines and comment existing ones).  
![appsettings](https://github.com/urbluemn/RecipeBook/blob/main/docs/appsetings.png)  
![DependencyInjection](https://github.com/urbluemn/RecipeBook/blob/main/docs/DependencyInjection.png)  
Then change extension methods in both projects to "UseSQLite" and not "UseSqlServer".

---
# Feel free to clone it and try it yourself!
