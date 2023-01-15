# [App4App2Grad](https://github.com/jnstockley/App4App2Grad)
Ruby on Rail group project made during a first semester, graduate-level CS course, CS:5820 - Software Engineering Languages and Tools. The application is a SaaS application that allows a student to submit applications to graduate school and allows students to interact with other students and faculty members through discussion and private messages faculty members. Throughout this project, we worked in an agile work environment in 3 sprints of approxamently 2 weeks in length. We create separate branches and pull requests for each of the features, and ensured they didn't break existing features through the use of BDD and TDD testing and with our CI/CD pipeline.

# [BTTN (Better Twitch.tv Notifications)](https://github.com/jnstockley/BTTN)
This is a Java program that uses [Twitch's API](https://dev.twitch.tv/docs/api/) to determine if a channel is live. The user can add any number of channels, using the program, to a JSON config file. Whenever the program is run it will use the Twitch API to determine if the channel is live. If the status of the channel has changed from not live to live, using data stored in the JSON file, it will send the user a mobile push notification using [Alertzy](https://alertzy.app). I felt the need to build such a program since I started to get annoyed at how delayed the 1st party Twitch notifications could be, especially for channels with large followers. I would miss the beginning of streams and join late with a feeling that I missed a lot of important content. This program can send a notification within a minute of the stream going live, depending on how many channels are being checked, as compared to Twitch's notification which could be delayed as long as 10+ minutes.

# [Vaccine Checker](https://github.com/jnstockley/Vaccine-Checker)
This is a Java program that uses Selenium WebDriver to scrape [https://vaccinespotter.org](https://vaccinespotter.org) to see if a COVID-19 Vaccine Appointment is still available based on data the user enters into a JSON config file. If the program finds a suitable appointment it will send the user an email, with a personalized link to see if the vaccine is available and then to book it. This program wouldn't have been possible without the [covid-vaccine-spotter GitHub project](https://github.com/GUI/covid-vaccine-spotter). This is the source code for the website that this program uses to determine if a vaccine could be available.

# Address Book

## [AddressBook](https://github.com/jnstockley/AddressBook)
   The backend for the Address Book REST API. Helps interface between java code and SQL database! It helps the CLI and REST interface connect to the MySQL database, where the address, occupations, and people are stored. This also helps with AES Encryption before being sent to the database.

## [AddressBook CLI](https://github.com/jnstockley/AddressBookCLI)
   This part is now deprecated. An Address Book that is stored on a MySQL server and takes full advantage of CRUD! It's a CLI version of the REST interface to allow users to before CRUD on the objects in the database

## [AddressBook REST](https://github.com/jnstockley/AddressBookREST)
   An Address Book that is stored on a MySQL server and takes full advantage of CRUD! It can be accessed by using a RESTful interface! This RESTful service was swagger documentation and can perform CRUD on the objects in the database. Also implements bundles to allow for the translation of static text.

## [AddressBook UI](https://github.com/jnstockley/AddressBookUI)
   This program builds off of the AddressBook REST application and adds a UI using AngularJS. Allows the user to easily perform all the same actions the REST service has in a usable user interface.
