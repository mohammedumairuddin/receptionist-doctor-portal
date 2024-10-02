
# Ruby on Rails Patient Management System

## Introduction
This Rails application provides two portals—one for receptionists and one for doctors. Receptionists can register and manage patients, while doctors can view patient data and a graph representing patient registrations over time. It also includes proper authentication and user roles.



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



