TaskMate - Task Management System
**TaskMate** is a powerful yet simple **Task Management System** built with Laravel. It allows **Admins to create and manage projects** while enabling **Users to track, update, and edit tasks** efficiently.  
Perfect for **small businesses and organizations** looking to streamline task workflows.


Features
✅ Admin Dashboard – Create, manage, and oversee projects.
✅ User Collaboration – Assign, update, and track tasks efficiently.
✅ Role-Based Access – Secure authentication with Admin and User roles.
✅ Task Prioritization – Set due dates, priorities, and status updates.
✅ Real-Time Notifications – Stay updated on project progress.
✅ Easy UI – Intuitive interface for seamless task tracking.

Use Cases
🔹 Small businesses managing multiple projects.
🔹 Teams collaborating on task assignments.
🔹 Individuals organizing personal or work-related tasks.

Tech Stack
Framework: Laravel 10
Authentication: Laravel Breeze / Fortify
Database: MySQL
Frontend: Blade, Tailwind CSS (or Vue.js if planned)
Real-Time Features: Laravel Echo + Pusher (for notifications)
Installation

Clone the repository:
git clone https://github.com/Jiban-Niraula/Project-I.git
cd Project-I

Install dependencies:
composer install
npm install && npm run dev

Configure environment:
cp .env.example .env
php artisan key:generate

Set up database and run migrations:
php artisan migrate --seed

Start the application:
php artisan serve

Contributing
Feel free to fork the project, open issues, or submit pull requests. 🚀
