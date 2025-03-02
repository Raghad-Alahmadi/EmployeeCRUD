# EmployeeCRUD

## Overview

EmployeeCRUD is a Razor Pages project built with .NET 8.0. It provides a simple interface to create, read, update, and delete employee records.

## Prerequisites

- .NET 8.0 SDK
- Visual Studio 2022

## Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Raghad-Alahmadi/EmployeeCRUD.git
    cd EmployeeCRUD


2. **Open the project in Visual Studio 2022:**

    - Launch Visual Studio 2022.
    - Select `File` > `Open` > `Project/Solution`.
    - Navigate to the cloned repository folder and select the `EmployeeCRUD.sln` file.

3. **Restore NuGet packages:**

    - In Visual Studio, go to `Tools` > `NuGet Package Manager` > `Package Manager Console`.
    - Run the following command to restore the required packages:
      ```bash
        Install-Package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore -Version 8.0.0
        Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore -Version 8.0.0
        Install-Package Microsoft.EntityFrameworkCore.SqlServer -Version 8.0.0
        Install-Package Microsoft.EntityFrameworkCore.Tools -Version 8.0.0



4. **Build the project:**

    - In Visual Studio, select `Build` > `Build Solution` or press `Ctrl+Shift+B`.

5. **Run the project:**

    - Press `F5` or click the `Start` button in Visual Studio to run the project.

## Usage

- Navigate to the application in your web browser.
- Use the interface to create, read, update, and delete employee records.

## Project Structure

- `Models/Employee.cs`: Contains the `Employee` model.
- `Pages/Employee`: Contains Razor Pages for CRUD operations.
- `Views/Employee/Create.cshtml`: Razor view for creating a new employee.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License.


    
