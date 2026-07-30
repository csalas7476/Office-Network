# Office-Network

This project simulates a real-world office network built in Cisco Packet Tracer. The environment consists of an office LAN with employee workstations connected to a dedicated server room hosting core network services, including DHCP, DNS, Email, Web, and FTPS servers. A firewall is configured to protect internal resources by preventing unauthorized devices from accessing the network.

The objective of this project was to gain hands-on experience designing, configuring, and securing a business network while demonstrating how employees can communicate and access internal company resources in a controlled environment.

<img width="1874" height="726" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/3415baa2-5f04-4162-9883-8c0f0435edfa" />

Project Overview:

This project simulates an office netowrk with multiple users, internal servers, and netowkr security protcols 

The main goals of this project were:
* Allow office users to access internal company resources 
* Enable email and communication between users
* Host a  private web server for internal access
* Restrict unathorized access from unknown users

Network Design:
Office Network (Left Side):
* 5 PCs representing employees
* Connceted to a switch for internal communication

Server Room / DATA Center (Right Side):
* Host core services; DCHP, DNS, Web, File Server, and Firewall
* All services are on a separate subnet for secuirty


Employees Access:
* All employees that are recognized and authorized will the company resources

<img width="1386" height="792" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/b3da9d5a-7a85-4dab-97f4-4c52bc42e7ce" />



Unkown User (Outside Network):
* Simulates an external/unathorized user
* Access is denied by the firewall (or not recognized by DCHP)

<img width="1410" height="763" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/dc957902-c1a9-4fdf-98fc-523256e8c9f3" />


Router (Internet)
* Routes traffic between internal network and internet 
* Firewall protects internal resources from external threats

Services Configured:

Service        |         Purpose

DCHP           |         Automatically assigns IP addresses to office PCs

DNS            |         Resolves internal domain names (e.g., mail.company.local)

Email Server   |         Allows user to send and receive emails internally

Web Server     |         Hosts a private internal website accessible by office users

File Server    |         Stores and shares company files

Firewall       |         Blocks unauthorized access from unknown users
