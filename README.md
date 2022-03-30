## Covid Vaccine Management System 

The Project is designed to accomodate three actors - Beneficiary, Vaccination Centres and District Offices.

All Actors have their individual Dashboards and Functionalities complete with Registration and Login Pages.

Technologies Used --
1. Backend : Spring Boot, Spring Security, JWT
2. Frontend : Angular 11, Bootstrap, HTML, SCSS
3. Database : MySQL

<h3> Getting Started </h3>

<h4>Backend Setup</h4>

1. Import co-VMS-Backend as Spring Boot Starter Project in IDE (Preferrably Eclipse).
2. Modify [application.properties](https://github.com/arshisaxena26/co-VMS/blob/master/co-VMS-Backend/src/main/resources/application.properties) file to update MySQL username and password.
3. Create database in MySQL with the name : covid19vms
4. Run the project as Spring Boot to create tables in the database.
5. Prepare Database -- Download [queries.sql](https://github.com/arshisaxena26/co-VMS/blob/master/queries.sql) file and import it in the database using : source pathTo/queries.sql;

<h4>Frontend Setup </h4>

Import Angular Project in VS Code and install ng-modules using : npm install --save-dev @angular-devkit/build-angular
