# Pierres Sweet and Savory Treats

#### A custom organizer allowing Pierre and other authorized users to create and link bakery items with flavors using a many-to-many SQL database.

#### By Daniel Ware

## Technologies Used

* C#
* Entity
* SQL
* .NET
* CSS

## Setup/Installation Requirements

* Clone repository from github
* Create an appsettings.json file in SweetAndSavory directory and add the following:
  { "ConnectionStrings": { "DefaultConnection": "Server=localhost;Port=3306;database=[Your_Database_Name_Here];uid=root;pwd=[YOUR_PASSWORD];" } }
* Navigate to SweetAndSavory directory
* Run dotnet restore
* Run dotnet ef migrations add Initial
* Run dotnet ef database update
* Run dotnet run to and open web browser to http://localhost:5000 to view

## Known Bugs

* CSS styling not showing up correctly in localhost:5000. Seems to display better in https://localhost:5001

## License

MIT  (c) 2022

## Contact Information

Daniel Ware <waredanielb@gmail.com>