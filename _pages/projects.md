---
permalink: /projects/
title: "Agent design project for mnk Games"
excerpt: "Development of an agent that plays on a 7x7 board, using decision algorithms to compete autonomously in a “Connect 4” type game. <br/><img src='/images/Mate_portada'>"
autor_profile: true
redirect_from:
  - /projects/
  - /projects.html
---


# **Agent design project for mnk Games**

Development of an agent that plays on a 7x7 board, using decision algorithms to compete autonomously in a “Connect 4” type game.


This project involves developing an agent that autonomously plays a mnk-type game on a 7x7 board, with the goal of forming a line of four consecutive pieces (similar to the classic “Connect 4” or “3 in a row”). Using tree theory and decision-making algorithms, the agent must face simulated or real opponents with a performance comparable to that of a person.



## **Project Features:**


- **Development language:** Matlab.

- **Implemented techniques:** Search and decision-making algorithms such as minimax and variants, as well as Monte Carlo trees and other optimization methods.

- **Evaluation:** The agent’s performance will be measured both in simulated games and in defense practice, where it must demonstrate its ability to compete against other agents.

- **Additional challenges:** The agent must comply with efficiency and accuracy restrictions to ensure that it plays intelligently, respecting the rules and response times.



<div style="display: flex; gap: 20px;">
  <div style="flex: 1; text-align: center;">
    <img src="/images/Mat_2players.jpg" alt="2 Players" style="width: 100%; max-width: 200px;">
    <p>2 Players</p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/images/Mat_time.jpg" alt="Clock" style="width: 100%; max-width: 200px;">
    <p>Clock</p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/images/Mat_Unopierde.jpg" alt="Points" style="width: 100%; max-width: 200px;">
    <p>Points</p>
  </div>
</div>

The requirements are that it has to be 2 players, that one loses points and the other wins, and that it has to be played on time.


<div style="text-align: center;">
  <img src="/images/proyect_mnk.jpg" alt="This is the image of our finished project running." style="width: 50%; max-width: 400px;">
</div>


--------------------------------------------



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
    <img src="/images/Progra_Login.jpg" alt="App Login" style="width: 100%; max-width: 200px;">
    <p>2 Players</p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/images/Progra_Boleto.jpg" alt="Create Ticket" style="width: 100%; max-width: 200px;">
    <p>Clock</p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/images/Progra_Cliente.jpg" alt="Create Customer" style="width: 100%; max-width: 200px;">
    <p>Points</p>
  </div>
</div>

Several JFrames are designed to allow user interaction with the system. **Main Menu:** Provides access to the client and administrator functionalities. **Administrator Login:** Protected with username and password. **Registration and Ticket Purchase Form:** Allows the client to register and purchase tickets, applying discounts based on the client's data.


<div style="text-align: center;">
  <img src="/images/proyect_mnk.jpg" alt="Flight registration by the administrator." style="width: 50%; max-width: 400px;">
</div>


The “Flight Ticket Management System in Java” database was designed to store all customer, flight, and ticket information. The connection was made through NetBeans and was structured with primary and foreign keys to maintain data integrity. In addition, the interface was updated to make parameterized SQL queries, which improves security and prevents vulnerabilities such as SQL injection.


<div style="text-align: center;">
  <img src="/images/Progra_ComprarBoleto.jpg" alt="The purchase of a ticket by the user." style="width: 50%; max-width: 400px;">
</div>