This is a JSP and Servlet web application project that connects to a MySQL database allowing users to perform CRUD operations on students. The project has been developed using MVC architecture with DAO design pattern.
Web browser submit a request to our servlet controller then it make use of the helper class called the student database utility, it talks to the db, data will come back to the controller, controller forwards the data to our JSP page which is our View, finally send the view back to the browser.
DAO
It's main purpose is for interfacing with the database using JDBC code, very common design pattern. it is called Data Accessor Object (DAO)


![Web Browser (2)](https://github.com/RandulaTharaka/Test/assets/60685092/1a22e6e5-c552-491c-a0ae-5f01a64c1ee7)

