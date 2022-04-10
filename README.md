**Pierre's Treats Tracker!**

#### By **Nathan Conn**

#### This program was designed specifically for Pierre's Bakery, a long time partner in development for the purpose of keeping a record of frequent customers and the orders they have placed.


## Technologies Used

* C#
* NET 5.0
* MVC
* MS Testing



## Description

Pierre's bakery continues to grow, and as such Pierre has seen a lot of regulars start to become...well, regular. This application will help Pierre track his most loyal customers by allowing them to sign-up and track their orders. Eventually, this will serve as the platform for these customers to gain points and receive discounts or free treats!

## Setup/Installation Requirements

* Clone repository.
* In the command line, run "dotnet restore" in the SweetandSavory directory.
* In the command line, run "dotnet build" in  the SweetandSavory and directory.
* In the command line, run "dotnet run" while in the SweetandSavory directory to run the program.
* You will need to create an appsettings.json file in order to use and store information into the database that is attached. Use the code below and replace the necessary fields with your information:

{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=DBNAMEHERE;uid=root;pwd=PASSWORDHERE;"
    }
}

* In the command line, run "dotnet ef migrations add Initial" (and label each one different with any update you make)
* In the command line, run "dotnet ef database update"


## Known Bugs

*Currently no known bugs.

## Contact Me

Let me know if you run into any issues or have questions, ideas, or concerns:
nconn34@gmail.com

## License

Copyright (c) 4/10/2022 Nathan Conn