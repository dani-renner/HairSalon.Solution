# Eau Claire's Salon 
### An independent project for Epicodus

#### Salon owners can see their stylists and which clients belong to which stylists.

#### By Dani Renner

## Technologies Used

* C#
* ASP.NET
* Entity
* Razor
* MySqlWorkbench

## Description

_This application uses a database hosted locally to store a list of stylists and their respective clients for salon owners to keep track of the goings-on in their salon!_

## Setup/Installation Requirements

* You can clone the repository to your desktop
* Open a SQL command line in a terminal. Copy and paste the contents of dani_renner.sql and hit enter.
* Navigate to the HairSalon directory
* Add a file called appsettings.json. In that file, you will need to add the following code:
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[dani_renner];uid=root;(pwd=[password if you have one]);"
  }
}
* Enter "dotnet restore" (without the quotes) in the terminal & hit Enter
* Enter "dotnet run" (without the quotes) in the terminal to start
* Ctrl + click the link that populates in the terminal to view the application in the webpage. It is probably http://localhost:5000/
* Use Ctrl + C in the terminal to quit the host and close out of the window in the browser.

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright © 2021 Dani Renner

All Rights Reserved