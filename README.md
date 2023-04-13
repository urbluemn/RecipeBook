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
To launch the whole app you need to launch one project at a time.  
1) Launch Auth server to start receiving tokens. You can login at Auth/Login and register you account at Auth/Register.
2) Launch API and you'll see Swagger window pops up, here you can pass access token and try every method.
3) Finally launch MVC project to get started.

---
Feel free to clone it and try it yourself!

# If you have any questions, contact me at:
![](https://badgen.net/badge/Discord/gregory/purple?icon=discord) http://discordapp.com/users/354960587555471372  
![](https://badgen.net/badge/LinkedIn/nickyaroshko/blue) https://www.linkedin.com/in/nickyaroshko/  
![](https://badgen.net/badge/Gmail/nickyaroshko/red) nyaroshko1404@gmail.com
