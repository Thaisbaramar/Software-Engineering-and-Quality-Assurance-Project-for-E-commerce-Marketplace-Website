# Software Engineering and Quality Assurance Project for E-commerce Marketplace Website

## Made by:
- **Thaís Martin Baramarchi**
- **Luiz Felipe Kormann**

## Supervising Professor:
- Dr. Mohammed Nazeh Al-Imam

---

## Project Overview:

This project aims to create an optimal e-commerce website that digitalizes a physical marketplace for a company. The website will help enhance product sales by offering functions such as user authentication, product catalog management, payment processing, and order tracking.

## Feasibility Study:

In line with client specifications, the primary goals for this project are divided into **functions**, **features**, and **budget planning**. The objectives are to create a seamless online marketplace with user-friendly navigation, security, and efficient transactions.

---

## Specifications

### Level 1 – Functional Requirements

| Customer Specifications   | Functions          | Features               | Budget    |
|---------------------------|--------------------|-------------------------|-----------|
| 1. User Authentication     | - User registration<br>- Login/logout<br>- User profile | - Integration<br>- Security | |
| 2. Product Catalog         | - Product listing<br>- Categories<br>- Filters | - Integration<br>- Management | |
| 3. Payment                 | - Cart<br>- Secure checkout<br>- Order confirmation | - Security<br>- Integration<br>- Notifications | |
| 4. Search                  | - Product search<br>- Sorting | - Integration<br>- Management | |
| 5. Authorization Levels    | - Define and control access permissions | - Integration<br>- Management | |
| 6. Error Handling          | - Specifying errors<br>- Defining error messages | - Management | |

---

### Level 2 – System Specifications

#### Software Requirements:

- **Operating Systems**: OS compatibility
- **Programming Language**: JavaScript
- **Frameworks and Libraries**: jQuery.js
- **Database**: SQL

#### Hardware Requirements:

- **CPU**: Minimum CPU configurations
- **Memory (RAM)**: Minimum DDR4 GB
- **Graphics**: Basic graphical processor
- **Internet Connection**: Stable 5 Mbps

---

### Non-Functional Requirements:

| Quality Measure | Features |
|-----------------|----------|
| Usability       | - Efficient use<br>- Intelligible interface |
| Security        | - User data privacy<br>- Payment security |
| Performance     | - Page load speed<br>- Scalability |
| Availability    | - Uptime during maintenance |
| Reliability     | - System uptime<br>- Data integrity |

---

### Scope and Audience:

The project aims to build an e-commerce website that caters to both the end-users and the company. By addressing both qualitative and quantitative requirements, the system is designed to optimize user experience, performance, and scalability. 

---

## Joint Report:

### Technical Requirements:

**Software:**
- OS: Windows Server
- DBMS: SQL
- Programming Language: JavaScript
- Third-party gateway integrations

**Hardware:**
- Server processing capabilities
- Storage and internet connection requirements

**Development Tools:**
- JavaScript for front-end and back-end
- jQuery.js for framework
- Payment gateway integrations

### Quality and Performance:

- **Page load time**: < 5 seconds
- **Transaction time**: < 1 minute
- **Database response time**: < 5 seconds
- **Uptime**: 99%

---

## Requirement Analysis:

### Function Metrics:

| Functions        | Non-Functional Requirements | Metrics                         |
|------------------|-----------------------------|----------------------------------|
| Registration      | Security                    | Response time, Success rate      |
| Login             | Security, Scalability       | Response time, Logins per day    |
| Search            | Correctness, Performance    | Response time, Keywords          |
| Add/Delete to Cart| Correctness                 | Response time, Conversion rate   |
| Payment           | Security, Performance       | Success rate                    |

---

## Data Structure & Class Diagram:

The system will include user classes like Buyer and Seller, along with Item and Order classes to manage purchases, listings, and transactions.

### Key Classes:

- **User**: Parent class for Buyer and Seller
- **Seller**: Can list items and manage inventory
- **Buyer**: Can browse items, add to cart, and make purchases
- **Item**: Stores product information
- **Order**: Manages checkout and shipping information

---

## Validation:

### Testing Phases:

- **White Box Testing**: Unit and subsystem testing to ensure the correctness of code.
- **Black Box Testing**: System integration testing to check full functionality.
- **Alpha Testing**: First release testing for basic functionality.
- **Beta Testing**: Pre-release testing to get feedback from real users.
- **Delta/Gamma Testing**: Final release testing with continuous monitoring for bugs.

---

## Keywords and Recommendations:

- **User Authentication**: Secure and user-friendly login system.
- **User Profile**: Easy-to-use interface for managing accounts and orders.
- **Product Catalog**: Full digital product listing with search functionality.
- **Cart**: Simple cart management for buyers.
- **Payment Processing**: Secure gateway for fast transactions.

---

### Conclusion:

This e-commerce marketplace website is designed to offer a seamless user experience with optimal performance, reliability, and security. The project focuses on delivering high-quality services while meeting the budgetary requirements.
