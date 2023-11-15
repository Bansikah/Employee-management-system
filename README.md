# Employee Management System with Flask

This is an Employee Management System built using Flask, a Python web framework. It provides a user-friendly interface for managing employee information and performing various administrative tasks. This README file provides an overview of the system's features and instructions for setting up and using the application.

## Features

1. **User Authentication**: The system supports user registration and login functionality to ensure secure access to the application. Each user is assigned a role (admin or employee) that determines their privileges within the system.

2. **Dashboard**: Upon logging in, users are presented with a dashboard that displays relevant information and quick access to various features. The dashboard provides an overview of the system's key metrics and notifications.

3. **Employee Management**: The system allows administrators to manage employee information efficiently. Key features include:

   - Add new employees: Admins can add new employees to the system by providing relevant details such as name, email, contact information, and job position.
   - View employee details: Admins can view the complete list of employees along with their details, such as name, email, contact information, job position, and date of joining.
   - Edit employee information: Admins can update employee details, such as contact information, job position, or any other relevant information.
   - Delete employees: Admins can remove employees from the system when necessary.

4. **Leave Management**: The system includes a leave management feature to handle employee vacation or absence requests. Key features include:

   - Submit leave requests: Employees can submit leave requests, specifying the start and end dates, reason, and type of leave (e.g., sick leave, annual leave, etc.).
   - Approve or reject leave requests: Admins can review and approve or reject leave requests submitted by employees. They can also add comments or provide additional information regarding the decision.
   - View leave history: Employees can view their leave history, including approved, pending, and rejected requests.

5. **Attendance Tracking**: The system provides a module for tracking employee attendance. Key features include:

   - Clock-in and clock-out: Employees can clock in and clock out to record their work hours.
   - Attendance report: Admins can generate attendance reports for individual employees or the entire workforce. These reports include details such as clock-in/out times, total hours worked, and any overtime hours.

6. **Task Management**: The system includes a task management feature to assign and track tasks for employees. Key features include:

   - Assign tasks: Admins can assign tasks to individual employees, specifying the task description, due date, and priority level.
   - Track task progress: Employees can update the status of assigned tasks as "In Progress," "Completed," or "Pending."
   - Monitor task status: Admins can monitor the progress of tasks, view completed tasks, and track pending tasks.

## Getting Started

To set up and run the Employee Management System, follow these steps:

1. Clone the repository: `$ git clone https://github.com/your-repo.git`
2. Navigate to the project directory: `$ cd employee-management-system`
3. Create a virtual environment: `$ python3 -m venv venv`
4. Activate the virtual environment:
   - For Windows: `$ venv\Scripts\activate`
   - For Unix or Linux: `$ source venv/bin/activate`
5. Install the dependencies: `$ pip install -r requirements.txt`
6. Set up the database:
   - Create a new PostgreSQL database.
   - Configure the database connection in the `config.py` file.
   - Run the migrations: `$ flask db upgrade`
7. Start the application: `$ flask run`
8. Open your web browser and visit `http://localhost:5000` to access the Employee Management System.

## Conclusion

The Employee Management System built with Flask provides a comprehensive set of features for efficient employee management. By utilizing this system, administrators can streamline their administrative tasks, track employee attendance, manage leaves and tasks, and generate salary reports. With its user-friendly interface, the system simplifies the process of managing employee information and promotes effective communication within the organization.