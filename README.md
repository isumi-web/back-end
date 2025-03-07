# Music-blog-back-end-laravel


## Project Description
This is a Music Blog application developed using the Laravel framework. The application allows users to manage music-related content such as albums and songs. There are two types of users:

1. **Artists**
   - Can add, update, and delete their own albums and songs.
2. **Admin**
   - Has full control to perform CRUD (Create, Read, Update, Delete) operations on all albums and songs.

## Features
- User authentication for Artists and Admins.
- Artists can:
  - Add new albums and songs.
  - Update their own albums and songs.
  - Delete their own albums and songs.
- Admins can:
  - View all albums and songs.
  - Perform CRUD operations on any album or song.
- Database integration for managing music data.
- **Security Features**:
  - Passwords are hashed using Laravel's built-in hashing mechanism for secure storage.
  - Authentication is secured with Web Tokens .
- **Field Validations**:
  - All input fields are validated to ensure data integrity (e.g., required fields, data types, and length constraints).

## Technologies Used
- **Framework**: Laravel
- **Frontend**: React + Vite
- **Database**: MySQL
- **Version Control**: Git & GitHub

## Usage
- Log in as an Artist to create and manage your albums and songs.
- Log in as an Admin to manage the entire application's content.
