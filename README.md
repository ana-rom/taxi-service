
<h1 align="center">Welcome to our Taxi Service, Mate!</h1>
<h1 align="center"><img src="img/main1.png"/></h1>


### ✨ Flexible and intuitively easy to use web application

If you are looking for a reliable and quick taxi service for business or pleasure, 
this smart and efficient software is ready to help!

### 🚕  Project overview

---
This application is **driver-friendly** working platform with registration, authentication and other CRUD operations. 
It is built as a **three-layered architecture**, consisting of:</br>
➡️  presentation (controllers level)</br>
➡️  business logic (service level)</br>
➡️  data logic layer (DAO level)</br>

The benefit of using this structure in our web-app is that - each tier can be updated or scaled as needed without impacting the other tiers according to SOLID design principles.
### 🚀 Technology solution

---
* Web server: Apache Tomcat ([v.9.0.50](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/) or later)
* Presentation: 
  * JSP
  * Java Servlet API ([v.4.0.1](https://mvnrepository.com/artifact/javax.servlet/javax.servlet-api/4.0.1))
  * JSTL ([v.1.2](https://mvnrepository.com/artifact/javax.servlet.jsp.jstl/jstl-api/1.2))
* Service: 
  * Java ([JDK v.11 or later](https://www.oracle.com/java/technologies/downloads/))
  * Maven ([v.3.8.0 or later](https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-compiler-plugin))
* Database: 
  * MySQL ([v. 8.0.22](https://dev.mysql.com/downloads/mysql/) community)
* IDE: IntelliJ Ultimate

### 🔎 Functionalities

---
> Add a driver (i.e. register driver via the form or just add a new one)</br>
> Add a car</br>
> Add a manufacturer</br>
> Add a driver to a car</br>
> Display all current driver's cars</br>
> Display all cars</br>
> Display all drivers</br>
> Display all manufacturers</br>
> Soft delete a car</br>
> Soft delete a manufacturer</br>
> Soft delete a driver</br>


### 🔅 How it works

You need only 3 steps to run this web-app!</br>

1️⃣ Initialize your project by creating a fork (i.e. clone it from GitHub) and then running the [init_db.sql](src/main/resources/init_db.sql) file in your DBMS. 
You can easily use Workbench or any other visual tool.</br>
2️⃣ Create a connection to you DBMS by filling out all needed fields in [ConnectionUtil](src/main/java/taxi/util/ConnectionUtil.java) file from util package.</br>
3️⃣ Configure your local Tomcat server. It is recommended to use Tomcat v.9.0.50.</br>
🎉 Run the application!

If you have any questions related to installation process, or you want to give feedback,  feel free to contact us!


<h3 align="center">Good Taxi Service for Good People</h3>
<h3 align="center"><img src="img/main2.png"/></h3>
