# Blood Bank Management System (bbms)

## Overview
The Blood Bank Management System (BBMS) is a software solution designed to streamline and automate the management of blood banks. It supports donor registration, inventory tracking, blood requests, transfusion records, and reporting functionalities to enhance the efficiency and reliability of blood bank operations.

## Features

- **Donor Registration:** Add and manage donor profiles with detailed information.
- **Blood Inventory Management:** Track blood donations, different blood groups, and inventory levels.
- **Blood Requests:** Facilitate requests and approvals for blood transfusions.
- **Transfusion Records:** Maintain records of issued blood units, patients, and medical staff.
- **Reporting:** Generate automated reports for inventory, donors, requests, and utilization statistics.
- **User Roles:** Accessible dashboard for admin, staff, and donors.

## Built With

- Python

## Getting Started

### Prerequisites

- Python , Django,SQLite
- asgiref==3.2.7, Django==3.0.5, django-widget-tweaks==1.4.8, pytz==2020.1, sqlparse==0.3.1


### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/mrsirjon/bbms.git
   ```
2. Install dependencies
   ```bash
   # Example for Python projects
   pip install -r requirements.txt
   ```
3. Set up the database
   ```bash
   # Example command
   python manage.py migrate
   ```
4. Start the development server
   ```bash
   # Example command
   python manage.py runserver
   ```

## Usage

- Register as a donor or administrator.
- Login to access the dashboard for managing blood inventory and requests.
- View and generate reports as authorized.


## Contributing

Contributions are welcome! Please submit issues, fork the repository, and create pull requests.

## License

 MIT

---

For questions or support, please contact [mrsirjon](https://github.com/mrsirjon).
