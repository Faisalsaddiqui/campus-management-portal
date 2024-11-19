### Campus Management System 🎓
The Campus Management System is a web application built with Laravel, Vue, PHP, and Blade, designed to simplify and manage campus operations. This system provides separate portals for admins and students, allowing administrators to manage subjects, attendance, and other academic details, while students can view their own progress and access limited campus information.
* WORK IN PROGRESS *
Installation instructions
```
npm install
```

```
composer install
```

```
npm run dev
```

```
php artisan migrate
```

```
php artisan db:seed
```
This will generate a User model with admin and super admin roles.
### Super Admin account Credentials:
Email: admin@mail.com
Password: password
Conventions
Every directory for Pages/Controller/Components correspond with a role. example: Pages/Student contains all pages associated with students.

## Features:
### Admin Portal:
Manage subjects and course content.
Track and update student attendance records.
Assign roles and permissions to users (admin, super admin, student).
Student Portal:
### View personal progress reports:
Access class schedules and subject lists.
View attendance records and grades.

Role-based Access:
Admins have full access to all management features.
Students have restricted access, only able to view their own information.
### Technologies Used:
Backend: Laravel (PHP)

Frontend: Vue.js, Blade

Database: MySQL (or other Laravel-supported databases)

Styling: CSS, Bootstrap
Usage
### Admin Tasks:
Log in as an admin or super admin using the provided credentials.
Navigate through the admin dashboard to manage subjects, update attendance, and assign roles.
### Student Tasks:
Log in as a student to view available courses, attendance records, and academic progress.
The student dashboard provides a streamlined view with limited access based on role.
### Conventions:
Each directory under Pages, Controller, and Components corresponds with a specific role.
Example: Pages/Student contains all pages associated with the student portal.
Shared components are stored in the shared directory for easy reuse across different parts of the application.
### Contributing:
Contributions are welcome! If you'd like to improve or extend the functionality of this project, please submit a pull request. Ensure that your code follows best practices and is well-documented. Any shared components will be in shared directory.
