<<<<<<< HEAD
<h2>MyProjects</h2>

<p align="center">
  <strong>A Laravel Web Application for Managing Personal Projects</strong>
</p>

<p align="center">
  Organize, manage, and track your projects in one place.
</p>

About The Project

MyProjects is a web application built with Laravel that allows users to manage their personal projects. Users can create, view, edit, update, and delete their projects through a simple interface.

Each user can access and manage only their own projects.

Features

<ul>
  <li>User authentication</li>
  <li>Create new projects</li>
  <li>View all personal projects</li>
  <li>View project details</li>
  <li>Edit existing projects</li>
  <li>Update project status</li>
  <li>Delete projects</li>
  <li>Project ownership protection</li>
  <li>Form validation</li>
</ul>

Technologies Used

<ul>
  <li><strong>PHP</strong> - Backend programming language</li>
  <li><strong>Laravel</strong> - PHP web application framework</li>
  <li><strong>MySQL</strong> - Database management system</li>
  <li><strong>HTML5</strong> - Page structure</li>
  <li><strong>CSS3</strong> - Styling</li>
  <li><strong>Bootstrap</strong> - Responsive interface</li>
  <li><strong>JavaScript</strong> - Frontend functionality</li>
  <li><strong>Composer</strong> - PHP dependency management</li>
  <li><strong>NPM</strong> - JavaScript dependency management</li>
</ul>

Requirements

Make sure you have installed:

<ul>
  <li>PHP 8.2 or higher</li>
  <li>Composer</li>
  <li>Node.js and NPM</li>
  <li>MySQL</li>
  <li>Laragon or XAMPP (optional)</li>
</ul>

Installation

1. Clone the Repository

git clone YOUR_REPOSITORY_URL

2. Navigate to the Project Directory

cd MyProjects

3. Install PHP Dependencies

composer install

4. Install JavaScript Dependencies

npm install

5. Create the Environment File

cp .env.example .env

For Windows PowerShell:

Copy-Item .env.example .env

6. Generate the Application Key

php artisan key:generate

7. Configure the Database

Create a MySQL database named myprojects.

Update the database configuration in your .env file:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=myprojects
DB_USERNAME=root
DB_PASSWORD=

8. Run Database Migrations

php artisan migrate

Running the Application

Start the Laravel development server:

php artisan serve

In another terminal, run the frontend development server:

npm run dev

Open your browser and visit:

http://127.0.0.1:8000
