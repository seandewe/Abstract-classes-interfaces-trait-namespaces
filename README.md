# Abstract-classes-interfaces-trait-namespaces
web interface with PHP sessions for login/logout.

PROJECT STRUCTURE
/user-management/
│── /App/
│ ├── /Core/
│ │ ├── AbstractUser.php # Abstract Class
│ │ ├── AuthInterface.php # Interface
│ │ ├── LoggerTrait.php # Trait
│ │
│ ├── /Models/
│ │ ├── Admin.php # Admin User Class
│ │ ├── RegularUser.php # Regular User Class
│ │
│ ├── /Services/
│ │ ├── AuthService.php # Handles authentication
│
│── index.php # Main file
│── autoload.php # Autoloader
