---
permalink: /projects_java/
title: ""
excerpt: "Development of an agent that plays on a 7x7 board, using decision algorithms to compete autonomously in a “Connect 4” type game. <br/><img src='/images/Mate_portada'>"
autor_profile: true
redirect_from:
  - /projects_java/
  - /projects_java.html
---


<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project with JAVA</title>
    <style>
        h1 {
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1></h1>
    </header>
</body>
</html>



# **Flight Ticket Management System in Java**

This project is a Java application for purchasing airline tickets, connected to a MySQL database, which allows managing clients, flights and reservations through a graphical interface and user roles.

In this project, a Java application was developed using the Object Oriented Programming (OOP) paradigm to manage the purchase of airline tickets. The application was connected to a MySQL database to store and manage customer, flight and ticket information.



## **Main Functionalities:**


- **Customer and Flight Registration and Administration:** CRUD (Create, Read, Update, Delete) functionalities were implemented for customers and flights. Customer data includes ID, name, and date of birth, which allows discounts to be calculated when purchasing tickets. For flights, details such as origin, destination, and other specific data are stored.


- **Ticket Management:** A class was created to manage tickets, allowing the customer to generate a ticket, verify seat availability, and store the information in the database. Verifications will be included to ensure that the customer is registered, and discounts will be applied for minors or seniors.


- **Seat Assignment and Control:** The system differentiates between VIP and tourist class seats, which are identified and marked in the database. The application verifies the occupancy of each seat, which allows for precise management of reservations for each flight.


- **User Roles:** Two main roles are configured, the customer role and the administrator role. Both roles have different permissions and accesses in the application, such as the administrator’s ability to delete flights or manage customer and flight information through specific graphical interfaces (JFrames).


<div style="display: flex; gap: 20px;">
  <div style="flex: 1; text-align: center;">
    <img src="/images/Progra_Login.jpg" alt="App Login" style="width: 100%; max-width: 300px;">
    <p>2 Players</p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/images/Progra_Boleto.jpg" alt="Create Ticket" style="width: 100%; max-width: 300px;">
    <p>Clock</p>
  </div>
</div>


<div style="flex: 1; text-align: center;">
    <img src="/images/Progra_Cliente.jpg" alt="Create Customer" style="width: 100%; max-width: 300px;">
    <p>Points</p>
</div>

Several JFrames are designed to allow user interaction with the system. **Main Menu:** Provides access to the client and administrator functionalities. **Administrator Login:** Protected with username and password. **Registration and Ticket Purchase Form:** Allows the client to register and purchase tickets, applying discounts based on the client's data.



<div style="text-align: center;">
  <img src="/images/Progra_RegistroVuelos.jpg" alt="Flight registration by the administrator." style="width: 50%; max-width: 400px;">
  <p>Flight registration by the administrator.</p>
</div>



The “Flight Ticket Management System in Java” database was designed to store all customer, flight, and ticket information. The connection was made through NetBeans and was structured with primary and foreign keys to maintain data integrity. In addition, the interface was updated to make parameterized SQL queries, which improves security and prevents vulnerabilities such as SQL injection.


<div style="text-align: center;">
  <img src="/images/Progra_ComprarBoleto.jpg" alt="Flight registration by the administrator." style="width: 50%; max-width: 400px;">
  <p>The purchase of a ticket by the user.</p>
</div>


