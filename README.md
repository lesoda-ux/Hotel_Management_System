# Hotel Management System

## 📚 Introduction

My name is **Stefano Caramagno**, and I'm pleased to present this repository containing a project on creation of a **hotel management system**. <br>
This project was completed as part of a **Software Engineering** course during my **Master's Degree in Computer Science and Engineering** at the **University of Catania**.

## ✨ Features 

- **Project Documentation**: Includes a written report detailing system requirements, architecture, and design choices.  
- **UML Diagrams**: Shows system design using Domain Model, System Sequence Diagrams, Sequence Diagrams, and Class Diagram.  
- **Responsive UI Design**: Ensures an adaptable interface optimized for both web and desktop screens.  
- **Software Architecture**: Implements the MVC pattern for modular and maintainable development.  
- **Object-Oriented Design Patterns**: Applies GoF Design Patterns and GRASP principles for better modularity and scalability.
- **Database Management**: Stores and manages data efficiently through a structured database system.  
- **Database Abstraction Layer**: Leverages ORM for efficient interaction with the database.  
- **RESTful API Integration**: Offers scalable APIs following REST principles for client-server communication.  
- **Secure User Authentication**: Implements a login and registration system for all user types.
- **User Account Access**: Limits Customers and Cleaning Staff to viewing and managing only their data.  
- **Shared Account Access**: Lets Receptionists and Operations Managers view and manage shared data.
- **Check Room Availability**: Allows customers to verify room availability before making or modifying a reservation.  
- **Request Booking**: Enables customers to submit a booking request for hotel rooms.  
- **Manage Booking Requests**: Allows receptionists to review and approve or reject customer booking requests.  
- **Make Payment**: Facilitates online payment transactions for confirmed booking requests.  
- **View Paid Bookings**: Enables customers to check their successfully paid reservations.  
- **Request Booking Modification**: Allows customers to submit modification requests for existing paid bookings.  
- **Manage Modification Requests**: Lets receptionists review and process requested paid booking changes.  
- **Cancel Booking**: Provides customers the option to cancel a paid booking before check-in.  
- **Delete Booking**: Enables receptionists to cancel paid bookings when necessary.  
- **Digital Check-In**: Allows customers to confirm check-ins for their paid bookings.  
- **Digital Check-Out**: Handles check-out procedures for departing guests.  
- **Assign Cleaning Tasks**: Enables the operations manager to assign room cleaning tasks to cleaning staff.  
- **Manage Cleaning Tasks**: Allows cleaning staff to update room cleanliness status after completing their tasks.
- **Robust Testing & Debugging**: Ensures reliability and stability through rigorous testing and debugging practices.

## 🛠️ Tech Stack

- **Diagram**: UML for system modeling and visualization.
- **Frontend Development**:  
  - **HTML** for structuring and organizing web content.  
  - **CSS** for styling, layout, and responsive design.  
  - **Tailwind CSS** for streamlined and modern styling.
  - **JavaScript** for handling user interactions and making requests to APIs.  
- **Backend Development**:  
  - **Java** for implementing server-side logic and processing data.  
  - **Spring Boot** for creating and managing API endpoints to handle client requests.  
- **Database Management**: MySQL for structured and efficient data storage.    
- **Testing Frameworks**: 
   - **JUnit** for unit testing and validating application logic.
   - **Mockito** for mocking dependencies and simulating interactions between objects.
- **Dependency Management**: Maven for installing and managing project dependencies.  
- **IDE**: Visual Studio Code for development and debugging.  
- **Version Control**: Git for tracking changes and managing project versions.  
- **Repository Hosting**: GitHub for storing, sharing, and maintaining the project repository.  

## 🚀 Getting Started

### Prerequisites

Ensure you have the following tools installed on your system before proceeding:

- **Java Development Kit (JDK)**: Version 17 or later, required to run the application.  
- **Apache Maven**: Used to install dependencies and build the project.
- **XAMPP**: Required to provide a local server environment with MySQL and Tomcat.  
- **Astah UML**: Required for viewing UML diagrams.  
- **IDE**: Required to read and understand code efficiently.  
- **PDF Reader**: Required to view the documents.  
- **Git**: Used to clone the repository.

### Installation Steps

1. **Clone the Repository**
   
   To download the repository and navigate to its directory:

   ```sh
   git clone https://github.com/stefanocaramagno/Hotel_Management_System.git
   cd Hotel_Management_System
   ```

2. **Start MySQL Server**

   To launch the MySQL server using XAMPP:

      - **Windows**

         ```sh
         C:\xampp\mysql\bin\mysqld --console
         ```

      - **Linux**

         ```sh
         sudo /opt/lampp/bin/mysql.server start
         ```

      - **macOS**

         ```sh
         sudo /opt/lampp/bin/mysql.server start
         ```

3. **Install Dependencies**

   To install all required dependencies:

   ```sh
   mvn clean install
   ```

### Running the Application

1. **Start the Server**

   To start the application:

   ```sh
   mvn spring-boot:run
   ```

2. **Access the Application**

   To open the application in your browser:

   ```sh
   http://localhost:8080
   ```

   This will take you to the homepage of the Hotel Management System.

### Testing the Application

To run the project's test suite:

```sh
mvn test
```

##  🌐 Connect with Me

Feel free to explore my professional journey, check out my projects, or get in touch through the following platforms:

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:stefano.caramagno@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%2300A36C?style=for-the-badge&logo=buffer&logoColor=white)](https://stefanocaramagno.vercel.app)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stefanocaramagno)
[![Indeed](https://img.shields.io/badge/Indeed-%2300A4CC?style=for-the-badge&logo=indeed&logoColor=white)](https://profile.indeed.com/p/stefanoc-4cl1mmq)
[![GitHub](https://img.shields.io/badge/GitHub-%232F2F2F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/stefanocaramagno)
[![YouTube](https://img.shields.io/badge/YouTube-D14836?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@stefanocaramagno)

## ⚖️ License

© **Stefano Caramagno**

**Personal and Educational Use Only**  
All content in this repository is provided for personal and educational purposes only. <br>
Unauthorized actions without explicit permission from the author are prohibited, including but not limited to:

- **Commercial Use**: Using any part of the content for commercial purposes.
- **Distribution**: Sharing or distributing the content to third parties.
- **Modification**: Altering, transforming, or building upon the content.
- **Resale**: Selling or licensing the content or any derivatives.

For permissions beyond the scope of this license, please contact the author.

**Disclaimer**  
The content is provided "*as is*" without warranty of any kind, express or implied. <br>
The author shall not be liable for any claims, damages, or other liabilities arising from its use.