# Online-Store

SOFTWARE DOCUMENTATION

Summary: This document describes the software development project for the Online Store Control System. The system aims to optimize store operations, facilitating the management of registrations, scheduling, customer service and financial information. This document details the system requirements, architecture, technologies used, user interfaces and workflows.

Page 1: Introduction / Project Objectives / Target Audience. Page 2: Functional Requirements / Architecture and technologies used / Functionality flow. Page 3: Use Case Diagram

Introduction - page 1:

This document presents the Online Store Control System project.

Project Objectives - page 1:

Automate the customer and product registration process. Allow the recording of information about customer payments and their respective purchases in Pix, Debit and Credit. Provide integrated financial control with recording of financial transactions. Improve operational efficiency and provide a more agile and organized customer service experience.

Target audience - page 1:

This document is intended for software architects, software engineers, and testers.

Functional Requirements - page 2:

Customer Registration: Allows the registration of new customers, including name, address, telephone number and other relevant information. Product Registration: Enable product registration in the online store. Sales Record: Allows you to record the dates of the last product sold, along with those that are available or not. Scheduling: Allows you to schedule products, allowing you to select available dates and times. Payment Control: Requires password to access the financial module. Allow recording of financial transactions, such as payments and receipts. Generates financial reports, such as cash balance and revenue. Friendly Interface: Provides an intuitive and easy-to-navigate graphical interface for attendants and system employees.

Architecture and technologies used - page 2:

The Online Store Control System was developed as a desktop application using the C# programming language. The graphical interface is created using the .NET Framework (WPF) framework. The database used is MySQL to store information locally.

Functionality flow - page 2:

Online store registration flow. Attendant (Employee) Flow. Financial control flow.

Use case diagram – page 3:

Use Case - Main Login Screen: Company Attendant Description: This use case describes the options available from entering the application to navigating through it.

Basic Flow:

The attendant starts the system and the Login and Registration screen is displayed. After logging in, the Menu screen appears at the top, with the following options: i - Payments: View a payment panel with credit, debit and pix cards (Requires access password). ii - Exit: Returns to the menu. The attendant selects one of the menu options.

Alternative Flows:

Option 1 – Registration: ii. The system opens three options, purchase registrations on Pix, Debit and Credit. ii. The attendant fills in the necessary data and confirms the customer's order registration. 4. The system saves the information in the database.

Option 2 - Payments:

v. The attendant selects the “Payments” option in the menu and opens “Credit”, “Debit” or “Pix”. saw. In both options, the system displays total accounts payable, all order records and other necessary information. viii. The system displays the results found on the screen if you want to search in this area. viii. The system saves the information in the database.

Program screens:
