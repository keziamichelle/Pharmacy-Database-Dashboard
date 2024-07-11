# Pharmacy Database Dashboard

## Project Overview
The Pharmacy Database Dashboard is a comprehensive solution designed to streamline pharmacy operations. It features user-friendly interfaces for both customers and administrators, allowing customers to manage accounts, place orders, and view purchase history, while administrators can efficiently handle drug management, customer information, and order processing. The project employs Streamlit for the interface and an SQLite database for robust data storage and retrieval.

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Project Objectives](#project-objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Introduction
The Pharmacy Database Dashboard project aims to enhance the effectiveness of pharmacy management by providing a centralized system that facilitates seamless customer interactions and efficient administrative tasks. It leverages modern web technologies to create an intuitive and responsive user interface, ensuring a streamlined user experience.

## Problem Statement
The current landscape of pharmacy management faces several challenges, including manual record-keeping and lack of a centralized system, leading to data discrepancies and inefficiencies. This project introduces a streamlined solution that leverages technology to enhance pharmacy management, providing an integrated, automated, and user-centric approach.

## Project Objectives
- Develop a user-friendly and efficient system for pharmacy management.
- Enable customer account management, drug administration, order processing, and provide an administrator dashboard.
- Facilitate seamless pharmacy management, customer interactions, and administrative tasks through a Streamlit interface, incorporating user authentication and efficient data handling with SQLite.

## Features
### Customer Account Management
- User registration with name, password, email, state, and phone number.
- Account login and authentication.

### Drug Management
- Addition, viewing, updating, and deletion of drug records.
- Display of detailed drug information, including name, expiry date, main use, and ID.

### Order Processing
- Customers can place orders, select drugs, and specify quantities.
- Storage of order details in the database, including customer name and items purchased.

### Administrator Dashboard
- Efficient management of drugs, customers, and orders.
- Real-time updates on inventory and order status.

### Database Connectivity
- Seamless connection to an SQLite database for efficient data storage and retrieval.

## Technologies Used
- **Front End**: Streamlit
- **Back End**: Python with SQLite database

## Installation
To run this project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/keziamichelle/pharmacy-database-dashboard.git
   ```

2. Navigate to the project directory:
   ```sh
   cd pharmacy-database-dashboard
   ```

3. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```

2. Follow the on-screen instructions to interact with the dashboard.


## Team Members
- Sandra B S (MUT21AD053)
- Nandika Prince (MUT21AD041)
- Sneha CM (MUT21AD055)
- Kezia Michelle George (MUT21AD034)
