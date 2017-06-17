# Biblioteczka
Decription in progress


## Getting Started
These instruction will help you to run this project on your local machine.

### Initialize Database 
After open project in Visual Studio you need to initialize database. There is a class in Models folder called LibraryContextSeedData.cs. which is responsible for creating initial database with example data.

```
In Visual Studio open Package Manager Console then write
* Enable-Migrations
* Add-Migration Initial
* Update-Database
```

After that commands, first user with example bookshelf and book on it are created.
