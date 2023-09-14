
# Maintenance Automation for LNMIIT Hostels

## Overview

The Maintenance Automation project aims to replace the manual, notebook-based complaint registration system in LNMIIT hostels with a streamlined, digitized solution. The project addresses the inefficiencies of the manual system, such as lack of categorization and tracking, by offering a comprehensive and user-friendly web application.

## Table of Contents

- [Features](#features)
  - [Complaint Categories](#complaint-categories)
  - [User Identification](#user-identification)
  - [Status Tracking](#status-tracking)
- [Modules](#modules)
  - [Admin Module](#admin-module)
  - [Engineer Module](#engineer-module)
  - [User Module](#user-module)
- [Technologies Used](#technologies-used)
- [Security Considerations](#security-considerations)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)


## Features

### Complaint Categories

- Mess Complaints
- Electrical Complaints
- Architectural Complaints
- Wi-Fi Complaints
- Washroom Complaints
- Hygiene Complaints

### User Identification

To register a complaint, users need to provide:

- Full Name
- Registration Number
- Gender
- Block
- Room Number
- Subject
- Complaint Details

### Status Tracking

After a complaint is registered, authorities can track its status and mark it as "Done" upon resolution.

## Modules

### Admin Module

- View and categorize incoming complaints.
- Assign complaints to appropriate engineers.

### Engineer Module

- View assigned complaints.
- Mark complaints as resolved and provide feedback.

### User Module

- Register new complaints.
- Track the status of registered complaints.

## Technologies Used

- PHP
- MySQL
- HTML, CSS, Bootstrap
- JavaScript

## Security Considerations

- Secure authentication for admins, engineers, and users.
- Encrypted password storage (pending implementation).
- SQL Injection protection (pending implementation).

## Installation

Follow these steps to get the Maintenance_Automation project up and running on your local machine:

### Prerequisites

- PHP 7.x or higher
- MySQL Server 5.x or higher
- PHPMyAdmin (for database management)

### Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/mihir32/maintenance-automation.git
    ```

2. **Navigate to Project Directory**
    ```bash
    cd maintenance-automation
    ```

3. **Install MySQL Server and PHPMyAdmin**
    - For Windows, you can use [XAMPP](https://www.apachefriends.org/index.html).
    - For macOS, you can use [MAMP](https://www.mamp.info/en/).
    - For Linux, you can install MySQL Server and PHPMyAdmin directly from the package repository.

4. **Create Database**
    - Open PHPMyAdmin, create a new database and import the `app.sql` file.

5. **Configure Database Connection**
    - Edit the `core/config.php` file to include your database details.

6. **Run the Application**
    - For Windows and macOS, start your XAMPP or MAMP servers and navigate to the project directory in the browser.
    - For Linux, move the project directory to `/var/www/html/` and start the Apache and MySQL services. Then, navigate to the project directory in the browser.

Congratulations! The application should now be running on your local server.


## Contributing

 - Feel free creating a fork or submitting a pull request.

## License
- General Open Source Licence (MIT)/
## Acknowledgements

We extend our heartfelt gratitude to the following individuals and institutions for their invaluable guidance and support throughout the development of this project:

- **Dr. Shweta Saharan**: For her academic guidance and constant encouragement.
- **Mr. Vikas Bajpai**: For his technical insights and hands-on support.
- **LNMIIT**: For providing an environment conducive to learning and innovation.

This project was a collaborative effort by Mihir Mishra, Aneesh Khunteta, Vinay Sunil Bhagwat, and was part of a college course at LNMIIT.
