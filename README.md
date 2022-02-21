<h1 align="center">Employee_Registration_Form_Using_Servlet_JSP_JDBC</h1>
<p style=color:blue align="center"> Created By : Ishika Singh &#128525; &#128525; &#128525;</p>
<br>
<p> This repositry consist of simple web-based module written in Java using Servlet , JSP, JDBC,MySQL </p>
  <h3> Features of Employee Registration form : </h3>
  <ul>
  <li> Create a employeeregister.jsp having fields (like firstName, lastName ,username ,password ,address,contact) </li>
  <li> Submit Employee Registration form with a POST request and URL - /register </li>
  <li> After form submission corresponding servlet will get called - EmployeeServlet.java </li>
  <li> Add dependencies to the lib folder
    <ul>
      <li> mysql-connector-java-8.0.13.jar </li>
      <li> servlet-api.2.3.jar </li>
      <li>  jstl-1.2.jar</li>
      <li> jsp-api.2.3.1.jar</li>
    </ul>
  </li>
  <li> EmployeeServlet class handles all the request parameters and send it to the EmployeeDao class to save this data to the database </li>
</ul>  
<h2> Fig.1 shows  Employee Registration JSP page </h2>
![1](https://user-images.githubusercontent.com/91179905/154996931-fa9c26c6-76fd-4e89-bc5b-332390fc676d.JPG)
<h2> Fig.2 shows  Employee Registered Successfully page </h2>
![2](https://user-images.githubusercontent.com/91179905/154996939-a788028a-64c8-4bcc-9370-50bc24aff87d.JPG)
<h2> Fig.3 shows  Data Inserted into MySQL Database page </h2>
![3](https://user-images.githubusercontent.com/91179905/154996946-32b6e539-688d-42b6-9177-8438df0b0d7f.JPG)

