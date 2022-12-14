![](https://scontent.fifo4-1.fna.fbcdn.net/v/t1.15752-9/300976506_933912847542593_7856539954076549827_n.png?_nc_cat=100&ccb=1-7&_nc_sid=ae9488&_nc_ohc=fm4jnQ4gwn0AX_wTPg_&_nc_ht=scontent.fifo4-1.fna&oh=03_AVJG51EzybZsg-P1Qrru94P8Oe5ooYSrK-cWKj-S9cl7YA&oe=63336889)
# Project description:
This web application is a simple taxi service simulation that requires registration or authentication process for access and includes other necessary CRUD operations.
# Features:
➩ registration as a driver;

➩ login as a driver;

➩ logout;

➩  create / update / remove:
* a car
* a driver
* a manufacturer

➩ add driver to a car;

➩ display a list of all:
* cars
* drivers
* manufacturers

➩ remove driver from a car.

# Structure:
Project uses a three-tier architecture with following layers of functionality:

* Controller: processes users' requests and responds to them;
* DAO: operates with data in DB;
* Service: contains all business logic of the application.

# Application technologies:
* JDK **11**
* Apache Maven **3.8.5**
* Apache Tomcat **9.0.65**
* MySQL **8.0.30**
* JDBC
* JSTL **1.2**
* Java Servlet API **4.0.1**
* JSP
* HTML, CSS

# Usage:
Project assumes that you've already installed:

* JDK (*version 11 or higher*)
* Apache Maven
* Apache Tomcat (*version 9.0.65*)
* MySQL
1. Clone this project to your IDE and check errors in *pom.xml* file (if needed):

   `git clone https://github.com/RomanPlk/taxi-service-app`
2. Create schema and tables in DB (use file *init_db.sql* in resources folder).
3. Set up connection to your DB in **ConnectionUtil class** (util package).
4. While configuring Tomcat, please, select *war exploded* artifact to deploy and change application context to **"/"**.
5. Run Tomcat and fell free to test the app.

# UML diagram for DB:
![](https://scontent.fifo4-1.fna.fbcdn.net/v/t1.15752-9/305172165_660556542104337_4541137526640143952_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=ae9488&_nc_ohc=kahsbrex5zIAX8KBsv8&_nc_ht=scontent.fifo4-1.fna&oh=03_AVKdn7sEZZquX5bM_n8KoZV6SAM8x5UvBqsm49pp49vRpA&oe=633AB2FD)
