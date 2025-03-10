### Hotel-Management-System-Using-Microsoft-Access-Database

This is a simple desktop application for managing a hotel, built with C# and the .NET Framework/.NET Core.The application aims to efficiently manage reservations, accommodation, accommodation history, rooms and customers, automating administrative processes. It allows entering, modifying and deleting reservations, tracking room status and calculating prices based on the number of days and room type.

## Technologies Used

- **C#** - Programming language used for developing the application.
- **.NET Framework/.NET Core** - Development platform.
- **Visual Studio** - IDE used for development.
- **Microsoft Access** - Database for storing room and reservation information.

## Installation

1. **Clone the Repository**
   - To get started with the project, clone the repository using the following command:
     ```bash
     git clone https://github.com/Adrian21203/Hotel-Management-System-Using-Microsoft-Access-Database.git
     ```

2. **Install Dependencies**
   - Make sure you have [Visual Studio](https://visualstudio.microsoft.com/) installed with support for C# development.
   - Open the project folder in Visual Studio.
   - If the app uses NuGet packages, run the following command:
     ```bash
     dotnet restore
     ```

3. **Set Up the Database**
   - The application uses **Microsoft Access** for storing data.
   - Ensure you have Microsoft Access installed or use **Microsoft Access Database Engine** if you don’t have Access installed.
   - The database file is located in the project folder. Ensure the connection string in the application is properly set to point to the `.accdb` file.

4. **Configure the Database Connection**
   - Open the connection string in the application’s configuration settings (e.g., `app.config` or `appsettings.json`).
   - Update the path to the Access database file (`AplicatieHotel.accdb`).

## Features

- **Room Management**: Allows adding, editing, and deleting available rooms in the hotel.
- **Reservations**: Allows users to make reservations for rooms and view current bookings.
- **Data Storage**: Data is stored in a Microsoft Access database.
- **Customer Management:**: Store customer information, such as name, contact details, and reservation history.
- **Search & Filter Functionality**: Search for rooms based on criteria like room type, price, and availability.

## Screenshots

Here are some screenshots of the application:

![Screenshot 1](Screenshots/image1.png)
![Screenshot 2](Screenshots/image2.png)
![Screenshot 3](Screenshots/image3.png)
![Screenshot 4](Screenshots/image4.png)
![Screenshot 5](Screenshots/image5.png)

## License

This project is licensed under the [MIT License](LICENSE).
