# Porting an Invoice and Billing Platform for Government Universities from Ionic to React Native

<img src="https://sdrive.blr1.cdn.digitaloceanspaces.com/files/e9ea3dadcdc13adf23ff7751e9701929.jpg" width="full" />

This README provides an overview of the project, including team details, relevant links, tasks completed, tech stack, key features, and steps to run the project locally.

## Team Details

**Team Name:** HEXA-CODE

**Team Leader:** [@tanyaguptaaaa29](https://github.com/tanyaguptaaaa29)

**Team Members:**

- **MEMBER_1** - 2023UEE4648 - [@tanyaguptaaaa29](https://github.com/tanyaguptaaaa29)
- **MEMBER_2** - 2023UEE4661 - [@yashmit789](https://github.com/yashmit789)
- **MEMBER_3** - 2023UCS1685 - [@Krish-Garg01](https://github.com/Krish-Garg01)
- **MEMBER_4** - 2023UEC2596 - [@SuryanshKS](https://github.com/SuryanshKS)
- **MEMBER_5** - 2024UCS1700 - [@dev-nihalsharma](https://github.com/dev-nihalsharma)
- **MEMBER_6** - 2024UCA1953 - [@sujallchaudhary](https://github.com/sujallchaudhary)

## Project Links

- **Internal Presentation:** [Internal Presentation](/files/Internal_PPT_HEXA-CODE.pdf)
- **Final SIH Presentation:** [Final SIH Presentation](/files/SIH_PPT_HEXA-CODE.pdf)
- **Video Demonstration:** [Watch Video](https://youtu.be/pIS_WHIDuQg)
- **Source Code:** [GitHub Repository](https://github.com/dev-nihalsharma/sih24-r1-invoicely)

## Tasks Accomplished

- [x] **User Roles & Access Control:**Port the role-based access control system that allows users like administrators, finance officers, and department heads to perform specific tasks related to invoices and billing.
- [x] **Invoice Management:** Migrate the invoice creation, tracking, and management features. Ensure the ability to handle multiple line items, taxes, discounts, and notes, with a smooth UI/UX transition.
- [x] **Reporting & Analytics:** Transition the reporting and analytics module, providing real-time insights into financial health, outstanding invoices, revenue forecasts, and audit trails.
- [x] **Security Enhancements:**Implement security features in React Native, including data encryption, secure user authentication, and compliance with data protection regulations.
- [x] **Responsive Mobile UI/UX:**Leverage React Native’s capabilities to provide a more responsive and intuitive user experience on both iOS and Android devices, with native-like performance and smoother animations.

# Tech Stack Overview

This project utilizes a variety of technologies to build a scalable, efficient, and user-friendly application. Below is an overview of the tech stack used and the reasons behind choosing each technology.

## [Node.js](https://nodejs.org/)

**Why Node.js?**  
Node.js was chosen for its non-blocking, event-driven architecture, which is perfect for building scalable and high-performance server-side applications. Its vast ecosystem and the ability to use JavaScript both on the front-end and back-end make development more streamlined and efficient.

**Use Case:**  
Node.js is used to handle server-side logic, manage API endpoints, and interact with databases.

## [React Native](https://reactnative.dev/)

**Why React Native?**  
React Native allows us to build mobile applications that work seamlessly across both iOS and Android with a single codebase. This reduces development time and ensures consistent functionality across platforms. Its ability to use JavaScript and a rich set of pre-built components speeds up the development process.

**Use Case:**  
React Native is utilized to create a cross-platform mobile app with native performance and user experience.

## [DigitalOcean](https://www.digitalocean.com/)

**Why DigitalOcean?**  
DigitalOcean is chosen for its simplicity, scalability, and cost-effectiveness. It provides a reliable cloud infrastructure that can easily scale as the application grows. Its user-friendly interface and extensive documentation make it easy to manage and deploy applications.

**Use Case:**  
DigitalOcean hosts the backend server and database, providing a scalable and secure environment for the application.

## [MySQL](https://www.mysql.com/)

**Why MySQL?**  
MySQL is a powerful, open-source relational database management system that offers high performance, reliability, and ease of use. Its wide adoption and robust community support make it a trusted choice for handling structured data.

**Use Case:**  
MySQL is used to store and manage relational data for the application, ensuring data integrity and efficient querying.

## [JWT (JSON Web Token)](https://jwt.io/)

**Why JWT?**  
JWT is used for securely transmitting information between parties as a JSON object. It helps in implementing authentication and authorization by allowing stateless sessions and ensuring data integrity. Its compact, URL-safe format is ideal for modern web applications.

**Use Case:**  
JWT is used for managing user authentication and maintaining secure, stateless sessions across different parts of the application.

## [Sequelize](https://sequelize.org/)

**Why Sequelize?**  
Sequelize is a promise-based Node.js ORM (Object-Relational Mapper) that supports multiple SQL dialects. It simplifies database interactions by providing an easy-to-use API for querying and manipulating data, and it includes features for model definition, migrations, and associations.

**Use Case:**  
Sequelize is used for managing database operations in the Node.js application, including defining models, running migrations, and executing queries in a more structured and efficient manner.

## Local Setup Instructions

This repository contains a Node.js server and a React Native app built with Expo.

## Prerequisites

- Node.js (v14.x or later)
- npm or yarn
- Expo CLI

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/dev-nihalsharma/sih24-r1-invoicely.git
   cd sih24-r1-invoicely
   ```

2. **Set Up the Node.js Server**

   - Navigate to the `server` directory:

     ```bash
     cd server
     ```

   - Install dependencies and start the server:

     ```bash
     npm install
     npm start
     ```

   The server runs on `http://localhost:3000`.

3. **Set Up the React Native App**

   - Navigate to the `invoicely` directory:

     ```bash
     cd ../invoicely
     ```

   - Install dependencies and start the Expo app:

     ```bash
     npm install
     npm start
     ```

   Open the app using Expo Go on your mobile device or an emulator.

## Notes

- Ensure both the server and app are running.
- Your mobile device should be on the same network as your development machine.
