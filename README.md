# Management System - Book Store

## Introduction

Welcome to the Book Store Management System, a .NET Core MVC project using Entity Framework. This system allows users to manage a book store by performing various tasks such as user authentication, adding genres, authors, publishers, and books.

## Features

- **User Authentication:** Users can register and login to the system, allowing for personalized interactions.

- **Genre Management:** Easily add, edit, and delete genres to categorize books effectively.

- **Author Management:** Manage information about authors, including their name, biography, and other relevant details.

- **Publisher Management:** Keep track of publishers and their details for better organization.

- **Book Management:** Add new books, associate them with genres, authors, and publishers, and manage their information.

## Getting Started

1. **Prerequisites:**
   - Install [.NET Core](https://dotnet.microsoft.com/download).
   - Set up a database for Entity Framework.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/razasoneji/BookStore-Management-System.git
   cd bookstore
3. **Database Setup:**
  - Update the connection string in appsettings.json to point to your database.
    ```bash
    "ConnectionStrings": {
     "DefaultConnection": "your-connection-string"
    }
  - Run Entity Framework Migrations:
    ```bash
    Update-Database
4. **Run the Application:**

## ER Diagram

![ER-diagram](https://github.com/user-attachments/assets/e7c08435-d565-4a22-9555-1a63570348fc)

## Project Structure

-Here's the project structure:

```plaintext
BookStore/
│
├── Connected Services/        # Connected services like Azure, APIs
├── Dependencies/              # NuGet package dependencies
├── Properties/                # Project properties (assembly info, launch settings, etc.)
├── wwwroot/                   # Static files (CSS, JS, images, etc.)
├── Areas/                     # Optional MVC areas for modular functionality
├── Controllers/               # MVC controllers to handle HTTP requests
├── Migrations/                # Entity Framework Core migration files
├── Models/                    # Domain models representing database entities
├── Repositories/              # Repository classes to handle data access
├── Screenshots/               # Screenshots or images (optional folder)
├── Views/                     # Razor views for UI rendering
├── appsettings.json           # Application configuration (e.g., database connection strings)
└── Program.cs                 # Main entry point of the application


## ScreenShots
![login](https://github.com/user-attachments/assets/bbabbb1b-a58b-4913-b0c3-e84226a11980)


![register](https://github.com/user-attachments/assets/882fb5b5-219d-45d3-b9f9-c9033a30f74e)
![forgotpassword](https://github.com/user-attachments/assets/f8958aa5-ec8b-49e7-9578-2ee342c3a172)




![resendemail](https://github.com/user-attachments/assets/e8feac9f-1686-41a4-91c2-17a5d40b567d)


![manageaccount](https://github.com/user-attachments/assets/73c99a9b-501b-4699-81f1-8155f25a2720)
![addbook](https://github.com/user-attachments/assets/b40150f9-8e1c-4490-bc3e-cc489e64fb35)



![addgenre](https://github.com/user-attachments/assets/0948c622-9015-4150-b6f3-c9cf4d189341)

![addpublisher](https://github.com/user-attachments/assets/80c15513-7f4f-4120-b7d1-1c7c7e44f454)

![addauthor](https://github.com/user-attachments/assets/25560196-812e-4e23-994f-270caa6d22dd)

![authorlist](https://github.com/user-attachments/assets/e9738db6-7ec9-4d7a-af71-301cda3e4200)

![genrelist](https://github.com/user-attachments/assets/0dd9d257-ba84-4ca2-9aad-280c6806891a)

![publisherlist](https://github.com/user-attachments/assets/2c86e4a1-2676-4525-a74b-254519d381e5)

![booklist](https://github.com/user-attachments/assets/7ed1ee94-c85a-49ff-b818-c937ea283abf)

