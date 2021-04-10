# [Vaccine Checker](https://github.com/jnstockley/Vaccine-Checker)
This is a Java program that uses Selenium WebDriver to scrape [https://vaccinespotter.org](https://vaccinespotter.org) to see if a COVID-19 Vaccine Appointment is available based on data the user enters into a JSON config file. If the program finds a suitable appointment it will send the user an email, with a personalized link to see if the vaccine is available and then to book it. This program wouldn't have been possible without the (covid-vaccine-spotter GitHub project)[https://github.com/GUI/covid-vaccine-spotter]. This is the source code for the website that this program uses to determine if a vaccine could be available.

# Address Book

## [AddressBook](https://github.com/jnstockley/AddressBook)
   The backend for the Address Book REST API. Helps interface between java code and SQL database! It helps the CLI and REST interface connect to the MySQL database, where the address, occupations, and people are stored. This also helps with AES Encryption before being sent to the database.

## [AddressBook CLI](https://github.com/jnstockley/AddressBookCLI)
   This part is now deprecated. An Address Book that is stored on a MySQL server and takes full advantage of CRUD! It's a CLI version of the REST interface to allow users to before CRUD on the objects in the database

## [AddressBook REST](https://github.com/jnstockley/AddressBookREST)
   An Address Book that is stored on a MySQL server and takes full advantage of CRUD! It can be accessed by using a RESTful interface! This RESTful service was swagger documentation and can perform CRUD on the objects in the database. Also implements bundles to allow for the translation of static text.

## [AddressBook UI](https://github.com/jnstockley/AddressBookUI)
   This program builds off of the AddressBook REST application and adds a UI using AngularJS. Allows the user to easily perform all the same actions the REST service has in a usable user interface.
