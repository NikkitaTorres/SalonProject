# VendorOrder

Created By: Nikkita Torres

## Description 

The Hair Salon web application is designed to make it easier for the user to create and track employees (stylists) and clients that are assisgned to stylists. It accomplishes this by creating a one-to-many relationship, stemming from the stylist to the client.

## Technologies Used

* C#
* MySQL Workbench 8.0 CE
* HTML
* Razor Pages
* ASP.NET Core
* Entity Framework Core

## Setup/Installation Requirements

1. Clone [this](https://github.com/NikkitaTorres/SalonProject.git) repository to your desktop.
2. This project requires a file named "appsettings.json". Create this file at the top level directory of the project (HairSalon.Solution) by typing "touch appsettings.json" into your terminal.
3. After creating the file, add the follwing code to the file: {
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database="";uid=YOUR_USERNAME_HERE;pwd=YOUR_PASSWORD_HERE;"
  }
}
Make sure to replace the "" in the "database=""", "YOUR_USERNAME_HERE", and "YOUR_PASSWORD_HERE" with your own database name, username and password for MySQL Workbench.
4. Navigate to the VendorOrder folder and run "dotnet build" in the terminal to compile the code.
5. Use "dotnet restore" in both the VendorOrder directory to install necessary packages.
6. Use "dotnet run" in the VendorOrder directory to run the project.

## License

MIT License

Copyright (c) [2024] [Nikkita Torres]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.