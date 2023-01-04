# Gexam : Student Management System
This project is a student management system that allows administrators to manage student information and track student progress. The backend is built with Symfony..<br/>

# Getting Started
To get started with the project, follow these steps:<br/>

  1. Clone the repository:<br/>
        - git clone https://github.com/aminekedd/Gexam-main.git<br/>
  2. Install the dependencies:<br/>
        - cd Gexam-main<br/>
        - composer install<br/>
  3. Create a database and update the .env file with the correct database credentials.<br/>
  4. Run the database migrations:<br/>
        - php bin/console doctrine:migrations:migrate<br/>
        
  5. Start the frontend:<br/>
        - php bin/console server:run<br/>

- The server should now be running at http://localhost:8000.

# Built With
        - Symfony - The backend framework used
