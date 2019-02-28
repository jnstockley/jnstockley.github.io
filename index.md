## Welcome to jnstockley.github.io

My name is Jack Stockley. I have a love for computers and software. My first major project I have worked on is my [Address Book Java Program.](https://github.com/jnstockley/AddressBook) I also then made a second part of that program and impleted a RESTful API. I have called this program the [Address Book Rest](https://github.com/jnstockley/AddressBookREST), very creative I know. To learn more about these program scroll down. I am currently a high school student but am going to be starting my freshmen year at the Unviersity of Iowa as a Computer Science Major.

### Education

Currently I am a high school student in the suburbs of Chiago Illinois. I am currently a Senior. I have also been accepted to and am going to be enrolled at the University of Iowa this fall. At the University of Iowa I will be studying [Computer Science.](https://cs.uiowa.edu/) After my time I at the University of Iowa I plan on being a Computer Scientist or a Sotware Engingeer.

### Extracurricular  Activites
I was apart of the Cross Country team at my high school during my Sophmore and Junior year. I decided not to join my Senior year because I didn't like running but I should have join becuase I loved being apart of a team. I averaged about 10-15 hours a week with Cross Country. I also have a part-time job at a local grocery store as a Cashier. I started off as a Bagger and then got pormoted after 3 months of working there. I average about 15-20 hours per week at my job. I have also started a new role for the track team. I am curently the manager/ assitant coach. My dudites are to record times and add them to a spreadsheet so that people on the team can see how they progress.


### Languages I Know
- HTML (I know not really a programming laguage)
- CSS (I know not really a programming laguage)
- JavaScript
- Java
- Starting to dabble in Swift

### Laungues I plan On Learning
- Python
- PHP
- C#
- C++

## Major Programs
   ### Address Book
    Address Book CLI Version 1.0.2!
    How to use this program:
    1. Run the program in command prompt or a termianl depending on which OS you are on
    2. When prompted type in IP of your SQL server
    3. After enter user name and password
    4. Select which table and which method you want to use (Type 0 to exit program)

    What`s new in Version 1.0:
    1. New features:
     - Added ability to work with any SQL server
     - Added ability to enter personal username and password
     - When typing in password, password is hidden
     - Added ability to get multiple address, occupations, and people, with similar fields
     - Re-designed CLI
    2. Bug Fixes and many performance improvements
      - Re-designed back-end to handle new features and more to come in the future
      - Program should crash less often
  
    Version 1.0.1
    1. Bug Fixes
      - Occupation now shows up when requeting data from person table
      - Address ID didn`t show up correctly
      - When updating data it would override all previous data
      - Unable to leave field blank for keeping addressId and occupationId the same
      - Small typos fixes
    2. New feature
     - Better UI for updating addressId and occupationId

    Version 1.0.2
    1. New features:
     - Better UI for closing program
      - Better UI for going back to table selector
     - Added Credit
     - Added closing message
     - Added link to github page
  
    What`s to come in later versions
     - RSA Encryption with public and private key
     - More ways to manipulate the data on the mySQL server
     - Program Updater
     - Ability for program to produce logs
     - Better UI for inputing field name
     - Ability to create new addresses and occupations when adding a new person
  
    Any other questions tweet me on twitter @jackstockley_ and Ill add it here

    Find a bug please be sure to report it under the issues tab!

   ### Address Book REST
    Extremely Overdue Update!!!!! I lot has happened since I last posted an update! I had mys server up for a bit but currently it is   down due to a corrupted kernel on my sevrer! I am trying right now to recover the data on the server to save reinstall time! Wish me luck. I am also going to be working on rewritng this program to add new features to it once I have finished the CLI version! Thanks!

    Setup:
    1. Create mySQL server
    2. Install tomcat on server and add the AddressBookREST.war file to tomcat
    3. Change the ip`s, yes both, to you internal and or external ip
    4. Change user and pass to your mySQL user username and password
    5. In encryption create two diffrent random strings have to be 8 characters longs

    How to use:

    Get Methods:
      1. Open a browser ie. chrome
      2. Go to the URL of you server:8200/AddressBookREST/"table"
      3. The program will return JSON to you
      4. For get by id add the id to the end of the url

    All Methods:
      1. Install a program called postman
      2. Type in server:8200/AddressBookREST/"table"
      3. Select method (GET,PUT,DELETE)
      4. For put go to body
      5. Type in JSON manually
      6. For get by id or delete add the id number at the end of the url

    Any other questions tweet me on twitter @jackstockley_ and Ill add it here
