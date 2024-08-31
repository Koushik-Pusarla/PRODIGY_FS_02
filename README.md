# employee-management-system
A Django-based web application that performs CRUD operations for managing employee data. It allows users to add, view, edit, and delete employee records through a user-friendly interface, making it easy to maintain accurate employee information. Ideal for small to medium-sized organizations.

# Features

- Add Employees: Create new employee records with details such as name, position, department, and salary.
- View Employees: Display a list of all employees with their details.
- Update Employees: Edit existing employee records to update their information.
- Delete Employees: Remove employee records from the database.
- User Interface: A clean and responsive UI for managing employee data efficiently.

# Installation

To get a local copy up and running, follow these steps:

# Prerequisites

- Python 3.x
- Django
- SQLite (or your preferred database)

# Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-management-system.git

2. Navigate to the project directory:
   ```bash
   cd employee-management-system

3. Create a virtual environment:
   ```bash
   python3 -m venv venv

4. Activate the virtual environment:

On Windows:
venv\Scripts\activate

On MacOS/Linux:
source venv/bin/activate

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

6. Apply the migrations:
   ```bash
   python manage.py migrate

7. Run the development server:
   ```bash
   python manage.py runserver

8. Open your browser and go to http://127.0.0.1:8000/ to view the application.
