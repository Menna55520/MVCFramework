# MVC MiniFrameWork

## Description
This is an implementation of a mini framework using the MVC (Model-View-Controller) design pattern. The project reflects my personal understanding of MVC and includes a simple routing system to manage requests. The goal is to provide an organized structure for a basic web applications.

---
## Project Structure
```
├───app
│   ├───controllers
│   ├───core
│   ├───models
│   └───views
│       └───products
└───public
    └───assets
        ├───css
        ├───images
        └───js
```

---
## Components
- **`app/`**: The core application folder:
  - **`controllers/`**: Contains controllers like `Home.php` that manage the flow between models and views.
  - **`core/`**: Holds foundational files:
    - `App.php`: Implements the routing system and handles controller loading.
    - `Database.php`: Provides database connectivity using PDO.
  - **`models/`**: Contains models like `User.php` for managing data and interacting with the database.
  - **`views/`**: Holds views like `home.php` for displaying the user interface.
- **`public/`**: The public folder:
  - **`assets/`**: Contains static files like images (`cat.png`).
  - **`index.php`**: The main entry point, directing all requests through the routing system.

---
## Notes
- This project is an experiment to understand MVC, so it may have some limitations or minor issues.
- The routing system is simple and relies on URL parsing to determine the controller and method.
- Working on reuse this mini framework in projects .