# Library-Management-System
A Laravel-based book and author management system with borrow record tracking, search, and CRUD functionality.

Features 
Book Management
 Add, view, edit, delete books
 Paginated list of books
 Assign authors to books

Author Management
 Create, view, edit, delete authors
 Unique email constraint for authors
 Used in dropdown for book creation

Search & Filter for Books
 Search by book title or author name
 Filter by published year and genre

Borrow Records 
 Track borrowed books
 Add borrower name, borrow date, return date
 View all borrow records

UI/UX
 Built with Laravel Blade templates
 Styled using Bootstrap
 Basic layout with consistent navigation

Setup Instructions
Configure Database
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=library_db
DB_USERNAME=root
DB_PASSWORD=

Run migrations
php artisan migrate




Styled using Bootstrap

Basic layout with consistent navigation
