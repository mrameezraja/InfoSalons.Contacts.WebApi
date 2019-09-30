# Steps to run the project

1. Clone the project `git clone https://github.com/mrameezraja/InfoSalons.Contacts.WebApi`
2. Make sure if you have installed [DotnetCore SDK 2.2.4"](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.402-windows-x64-installer)
3. Build the solution to restore nuget packages
4. Create a database in sql server management studio `InfoSalonsContacts`
5. Change connection string in `appsettings.json` file of `InfoSalons.Contacts.Web.Host` project
6. Select `InfoSalons.Contacts.Web.Host` as `Set as startup project`
7. Open `Package Manager Console` and select `InfoSalons.Contacts.EntityFrameworkCore` project in dropdown
8. Run `update-database` command, this will create tables neccessary for application to run
9. Start the application from visual studio
10. After running web api head towards [angular app](https://github.com/mrameezraja/InfoSalons.Contacts.Angular)