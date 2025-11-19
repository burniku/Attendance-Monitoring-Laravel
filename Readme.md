# Simple Attendance Monitoring

## Description / Overview
Simple Attendance Monitoring is a Laravel-based web application that provides a basic system to manage attendance. Users can **add students**, **add teachers**, and **check attendance records**. It is a simple and clean example of Laravel CRUD operations and basic attendance tracking.

## Goals & Objectives
- Learn how to build a simple Laravel CRUD application.
- Understand routing, controllers, and Blade views.
- Practice database migrations and Eloquent ORM.
- Build a minimal interface for managing attendance.
- Implement basic validation and form handling.

## Features / Functionality
- **Add Students:** Register new students into the system.
- **Add Teachers:** Add teacher records for attendance assignment.
- **Check Attendance:** View recorded attendance logs in a simple table.

## Installation Instructions
1. **Clone the repository and navigate into the directory:**
     ```bash
   git clone https://github.com/burniku/Attendance-Monitoring-Laravel
   cd Attendance-Monitoring-Laravel
   ```
2.  **Install PHP dependencies:**
   ```bash
composer install
```
3.  **Run migrations (to create the database tables):**
   ```bash
php artisan migrate
```
4.  **Start the development server:**
   ```bash
php artisan serve
```
5.  **Open the application:**
   **Visit http://127.0.0.1:8000 to start using the Attendance Monitoring System**

# Usage

1. Go to the Students page to add new student records.
2. Go to the Teachers page to add teacher records.
3. Open the Attendance page to check or review attendance logs.

# Screenshots

![image](https://github.com/user-attachments/assets/56c54b80-1303-46aa-b0f5-4859a8ad6593)
![image](https://github.com/user-attachments/assets/454684f6-cbe0-49c6-824b-22f4db48bb41)
![image](https://github.com/user-attachments/assets/4432cb6a-fbae-446d-a7ee-e5a8adfb9698)
![image](https://github.com/user-attachments/assets/57ea7354-109b-4d59-964a-2055e4205901)
![image](https://github.com/user-attachments/assets/4542d4bc-6b26-4e5b-9ed9-8299e38602cc)

## Contributors

**Brandon Sean Gallardo**
**Jan Yuri Reyes**

## License

MIT License

Copyright (c) 2025 Brandon Sean Gallardo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
