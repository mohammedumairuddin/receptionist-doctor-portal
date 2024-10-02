
# Ruby on Rails Patient Management System

## Introduction
This Rails application provides two portals—one for receptionists and one for doctors. Receptionists can register and manage patients, while doctors can view patient data and a graph representing patient registrations over time. It also includes proper authentication and user roles.

## Features:
- **User Authentication**: Single login page for both receptionists and doctors.
- **Patient Management**: Receptionists can register, view, update, and delete patient records.
- **Patient Registration Graph**: Doctors can visualize the number of patients registered over time using a graphical interface.
- **Role-Based Access**: Receptionists and doctors have different permissions and views.

## Setup Instructions

### 1. Clone the Repository:
```bash
git clone <your-repo-url>
cd patient_management
```

### 2. Install Dependencies:
Use the `Gemfile` to install the required dependencies:
```bash
bundle install
```

### 3. Database Setup:
Ensure PostgreSQL is installed and configure the `database.yml` file in `config/`.

Create and migrate the database:
```bash
rails db:create
rails db:migrate
```

### 4. Run the Development Server:
Start the server using the following command:
```bash
rails server
```

## Usage
- **Receptionists** can log in, register new patients, and manage existing patient records.
- **Doctors** can log in and view patient registration trends using a graph visualization.

## Graphical Representation:
- The application uses a graph to show the number of patients registered over the last 7 days, viewable by doctors.

## Additional Functionalities:
Feel free to extend the project with added features such as email notifications, improved UI, or additional reporting capabilities.
