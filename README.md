# Steps to run the project

1. clone the project `git clone https://github.com/mrameezraja/InfoSalons.Contacts.WebApi`
2. Make sure if you have installed [DotnetCore SDK 2.2.4"](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.402-windows-x64-installer)
3. then build the solution to restore nuget packages
4. create a database in sql server management studio `InfoSalonsContacts`
5. change connection string in `appsettings.json` file of `InfoSalons.Contacts.Web.Host` project
6. then open `Package Manager Console` and select `InfoSalons.Contacts.EntityFrameworkCore` project in dropdown
7. then run `update-database` command, this will create tables neccessary for application to run
8. select `InfoSalons.Contacts.Web.Host` as `Set as startup project`
9. then start the application from visual studio
10. After running web api head towards [angular app](https://github.com/mrameezraja/InfoSalons.Contacts.Angular)