# Contact Manager App

The Contact Manager App is a C++ application designed to manage and organize user contact information efficiently. This application allows users to add, edit, search, delete, and display contact details, including phone numbers, email addresses, and physical addresses. The app is built using C++14 and leverages object-oriented programming principles to ensure modularity and maintainability.
This project was developed in the first year of university under the supervision of Dr Mahmoud Mahdi.
## Key Features
- **Add User**: Allows users to add new contacts by providing details such as user ID, first name, last name, gender, city, phone number, email address, and physical address.
- **Edit User**: Enables users to update existing contact information based on user ID, first name, or last name.
- **Search User**: Provides functionality to search for contacts using user ID, first name, or last name.
- **Delete User**: Allows users to remove contacts from the system based on user ID, first name, or last name.
- **Show All Users**: Displays a list of all contacts stored in the system, including their phone numbers, email addresses, and physical addresses.

## Class Structure
- **User**: Represents a contact with attributes such as ID, first name, last name, gender, city, added date, and vectors to store phone numbers, email addresses, and physical addresses.
- **Phone**: Represents a phone number with attributes such as phone number, type, and description.
- **Email**: Represents an email address with attributes such as email address, type, and description.
- **Address**: Represents a physical address with attributes such as place, type, and description.
- **Contact**: Manages a collection of `User` objects and provides methods to add, edit, delete, search, and display users.

## File Structure
- **Contact-Manager-App.cpp**: Contains the main function and user interaction logic.
- **User.h / User.cpp**: Defines and implements the `User` class.
- **Phone.h / Phone.cpp**: Defines and implements the `Phone` class.
- **Email.h / Email.cpp**: Defines and implements the `Email` class.
- **Address.h / Address.cpp**: Defines and implements the `Address` class.
- **Contact.h / Contact.cpp**: Defines and implements the `Contact` class, which manages the collection of users.

## Installation
1. **Clone the repository**:
   git clone https://github.com/M7md-Galal/Contact-Management-System.git
    
    
