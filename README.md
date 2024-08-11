# Bank Management System

## Overview

This is a simple Bank Management System implemented in C++. It provides a Command Line Interface (CLI) for managing bank customers, accounts, and branches. Users can log in as customers, bank managers, or admins to perform various operations based on their roles.

## Features

- **Customer Login**: Allows customers to access their accounts.
- **Bank Manager Login**: Enables bank managers to manage branch operations.
- **Admin Login**: Grants administrators access to add customers, accounts, and bank managers.
- **Branch Management**: Manage branch details and staff.
- **Bank Manager Management**: Add new bank managers.

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++, clang++)
- Make sure you have a development environment set up to compile and run C++ programs.

### Compilation and Execution

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/bank-management-system.git
    cd bank-management-system
    ```

2. **Compile the program:**

    ```bash
    g++ -o bank_management_system main.cpp
    ```

3. **Run the program:**

    ```bash
    ./bank_management_system
    ```

## CLI Usage

1. **Customer Login**
    - **ID**: Enter a valid customer ID.
    - **Password**: Enter the corresponding password.

2. **Bank Manager Login**
    - **ID**: Enter a valid bank manager ID.
    - **Password**: Enter the corresponding password.

3. **Admin Login**
    - **ID**: `admin`
    - **Password**: `adminpass`

    After logging in as an admin, you have the following options:
    - **Add Customer**: Enter customer details to add a new customer.
    - **Add Account**: Create a new bank account.
    - **Manage Branch**: View or update branch details and manage staff.
    - **Add Bank Manager**: Enter details to add a new bank manager.

## Code Structure

- **`main.cpp`**: Contains the main application logic and CLI implementation.
- **Classes**: Includes `Customer`, `Account`, `Branch`, `Bank`, and related classes with appropriate functionalities.

## Contributing

Feel free to fork the repository, make changes, and create pull requests. For major changes or feature additions, please open an issue to discuss before implementing.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by basic banking systems and CLI applications.
- Thanks to the open-source community for their contributions and tools.

