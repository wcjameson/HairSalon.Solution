# Hair Salon

#### By William Jameson

#### An organizational tool for Salon owners

## Technologies Used

* C#
* .Net
* Entity
* MySql

## Description

This webapp allows the user to add and organize different clients for different stylists, store the input in a database for future reference and alter or delete entries as needed.

## Setup/Installation Requirements

* Navigate to the github repository by following the url https://github.com/wcjameson/HairSalon.Solution
* You can clone the repository to your machine by following these steps
* In your terminal enter the following
* git clone https://github.com/wcjameson/HairSalon.Solution
* Install MySql
* You will need to use MySql Workbench to import the database schema with the .sql filetype, located in the HairSalon.Solution directory
* In MySql Workbench, navigate to the administration tab, and select Data Import/Restore
* Import from Self-Contained File (the schema with filetype .sql)
* Make sure to create a connection to the database schema that was imported
* Do this by creating an appsettings.json file in the HairSalon project directory
* It should look like this
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=william_jameson;uid=root;pwd={password};"
  }
}
* User id and password will be your own
* Open the project in your terminal, navigate to the HairSalon.Solution directory, and enter the following
* dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0
* dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2
* dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0
* dotnet restore
* dotnet build
* dotnet run
* Open your browser and navigate to http://localhost:5000/


## Known Bugs

* Currently no know issues

## License
MIT License

Copyright (c) [2022] [William Jameson]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contact Information

* Contact at <williamjameson90@gmail.com>