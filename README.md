# Clinic Appointment Management System

This project is a comprehensive solution developed during an employability assessment to tackle scheduling challenges in a private clinic. The system ensures efficiency, eliminates errors, and improves the user experience by managing appointments seamlessly.

## Features

- **User Roles**: Separate functionalities for patients, doctors, and admins.
- **Conflict-Free Scheduling**: Prevents double bookings and updates availability in real-time.
- **Appointment History**: Tracks and displays past appointments for patients.
- **Search & Filter**: Allows filtering appointments by date, specialty, or purpose.
- **Notifications (Optional)**: Sends real-time alerts for changes or confirmations.
- **Scalability**: Supports future enhancements and integrations.

## Technologies Used

- PHP => 8.0
- Composer
- Node.js and npm
- Database (MySQL, PostgreSQL, SQLite, etc.)

## Installation

Follow these steps to set up and run the project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/BrayanCondee/Assessment-V2.0.git

2. **Navigate to the Project Directory**:
    ```bash
    cd Assessment-V2.0

3. **Install dependencies**:
    ```bash
    composer install
------------------------------------------
    npm install
4. **Configure the variables**:
    ```bash
    cp .env.example .env

5. **Generate the application key**:
   ```bash
   php artisan key7.:generate

6. **Run migrations and seeders for Database**:
   ```bash
   php artisan migrate --seed

7. **Run front**:
   ```bash
   npm run dev
   
8. **Run development server**:
    ```bash
    php artisan serve
    
## Database

- **DB_HOST=** _mysql-3c260681-mysq-cloud-project.c.aivencloud.com_
- **DB_PORT=** _17803_
- **DB_DATABASE=** _assessment_
- **DB_USERNAME=** _avnadmin_
- **DB_PASSWORD=** _AVNS_dqJgPf_kGjogOVHiR35_
  
