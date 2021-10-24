# Factory

### By Nick Hennessy

## Technologies Used

* C#
* .NET 5.0
* ASP.NET Core MVC
* HTML 
* Bootstrap
* MySQL Workbench
* Entity Framework Core

## Description
This is an MVC web application for managing Machines and engineers in a factory. Each machine can be assigned many engineers who are qualified to maintain it, and each engineer can be assigned to as many machines as they are qualified to maintain.

## Setup and Installation
* Clone this repository and open in your favorite text editor
* Navigate to Factory.Solution/Factory
* Create the file Factory/appsettings.json and add the following code:
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=nick_hennessy;uid=root;pwd=[your password];"
  }
}
* Replace [your password] with your mysql password
* Run the command dotnet restore to install all necessary packages
* Select Import from Self-Contained File
* Run the command dotnet ef database update to create the database from the Migrations folder
* In the terminal, run the commands dotnet build, then dotnet run
## Known Bugs
Add engineer route in Machines/Details is not working
## License
MIT LICENSE
Copyright (c) 2021 Nick Hennessy

## Contact Information
njhnny@gmail.com