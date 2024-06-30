
# Gym Management System

### The Gym Management System is a web application developed using PHP that facilitates efficient management of gym operations, including member management, class scheduling, billing, and attendance tracking.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Gym Management System aims to streamline gym administration processes, enhancing operational efficiency and improving member experience. It provides robust functionalities for managing memberships, scheduling classes, tracking attendance, and handling billing tasks, all through an intuitive and user-friendly interface.

## Features

- **Member Management:** Add, edit, and delete member profiles with detailed information.
- **Class Scheduling:** Create and manage class schedules, assign instructors, and allow member enrollment.
- **Attendance Tracking:** Monitor member attendance for both classes and gym sessions.
- **Billing and Invoicing:** Generate invoices for memberships, track payments, and send reminders.
- **User Authentication:** Secure login system for administrators and members.
- **Reporting:** Generate reports on attendance, revenue, and class participation.

## Installation

1. Clone this repository:

   ```shell
   git clone https://github.com/sahilshukla3003/gym-management-system.git
   cd gym-management-system
   ```

2. Import the database schema from `database.sql` into your MySQL database.

3. Configure the database connection in `config.php` with your MySQL credentials.

4. Start a PHP development server:

   ```shell
   php -S localhost:8000
   ```

5. Open a web browser and navigate to [http://localhost:8000](http://localhost:8000) to access the Gym Management System.

## Usage

### Admin Panel:

- Log in as an administrator using your credentials.
- Manage members, classes, attendance, billing, and generate reports.

### Member Portal:

- Members can log in to view class schedules, enroll in classes, and check their attendance history.

## Technologies Used

- **PHP:** Backend scripting language for server-side logic.
- **MySQL:** Database management system for storing gym data.
- **HTML/CSS:** Frontend technologies for designing user interfaces.
- **JavaScript:** Optional for client-side interactions and dynamic content.

## Contributing

Contributions to the Gym Management System are welcome! If you wish to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request with a clear description of your changes.

## License

This project is licensed under the [APACHE 2.0](LICENSE).
