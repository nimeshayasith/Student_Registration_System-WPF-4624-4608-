# Student Registration System

This is a desktop application developed in C# and Windows Forms, implementing the MVVM (Model-View-ViewModel) pattern for a clean and organized architecture. The application allows for student registration and management.

## Features

- **Login Screen:** Users can log in with their username and password, which is verified against the stored password in the database.
- **CRUD Operations:** Users can perform CRUD operations (Create, Read, Update, Delete) for entities. For example, in a POS system, users can manage products.
- **Entities:** The system includes at least two entities. For example, in a student registration system, there would be a "User" entity for login and a "Student" entity for student information.
- **Business Logic:** Bonus marks were given for implementing business logic in the system.

## Technologies Used

- **Framework:** Windows Forms
- **Pattern:** MVVM (Model-View-ViewModel)
- **Language:** C#
- **Database:** SQLite
- **ORM:** Entity Framework

## Project Structure

The project follows the MVVM pattern, separating the concerns of the application into models, views, and view models.

- `Models/`: Contains the classes that represent the entities in the application.
- `Views/`: Contains the Windows Forms for the user interface.
- `ViewModels/`: Contains the view models that handle the logic for the views.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/nimeshayasith/Student_Registration_System-WPF-4624-4608-.git`
2. Open the solution in Visual Studio.
3. Build the solution to restore the NuGet packages.
4. Run the application.

## Videodemo
[![Video Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID_HERE/0.jpg)](https://youtu.be/sWgjpQjwSQI)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

