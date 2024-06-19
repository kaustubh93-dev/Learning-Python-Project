# Contact Book Application

[![powered by](https://img.shields.io/badge/Powered%20by-Python%203-blue)](https://www.python.org/)

## Overview
The Contact Book Application is a Python-based console program that allows users to manage their contacts efficiently. It provides features for adding, viewing, searching, updating, and deleting contacts.

## Technologies Used
This application is built using the following technologies:<br>
- **Python:** The core programming language used for development.
- **Object-Oriented Programming (OOP):** Utilized for structuring the code using classes and objects.
- **Console Interface:** The application operates through a console-based interface for user interaction.

## Working of the Application
The Contact Book Application offers the following functionalities:<br>
1. **Add Contact:** Users can add a new contact with details such as name, phone number, email, and address.
2. **View Contacts:** Displays a list of all saved contacts along with their names and phone numbers.
3. **Search Contact:** Allows users to search for contacts by name or phone number, and displays matching results.
4. **Update Contact:** Enables users to update contact details, including name, phone number, email, and address.
5. **Delete Contact:** Provides an option to delete a contact from the contact list.

The application maintains a list of **'Contact'** objects within a **'ContactBook'**. Each Contact has attributes for name, phone number, email, and address.

## How To Use
**1. Clone the repository**
```bash
git clone https://github.com/kaustubh93-dev/Learning-Python-Project.git 
cd Learning-Python-Project\Contact Book Application
```

**2. Run the application**
```
python contactbook.py
```

**3. Interact with the application**
- The application will display a menu with options numbered from 1 to 6.
- Enter the number corresponding to the action you want to perform.

**Example Usage**<br><br>
**3.1. Adding a Contact**
```mathematica
Enter your choice: 1
Enter name: John Doe
Enter phone number: 123-456-7890
Enter email: john.doe@example.com
Enter address: 123 Main St, Cityville
```

**3.2. Viewing Contacts**
```yaml
Enter your choice: 2
Name: John Doe, Phone: 123-456-7890
```

**3.3. Searching for a contact**
```yaml
Enter your choice: 3
Enter name or phone number to search: Doe
Name: John Doe, Phone: 123-456-7890
```

**3.4. Updating a contact**
```mathematica
Enter your choice: 4
Enter the name of the contact to update: John Doe
Enter new name: John Doe Jr.
Enter new phone number: 987-654-3210
Enter new email: john.jr@example.com
Enter new address: 456 Oak St, Townsville
```

**3.5. Deleting a contact**
```mathematica
Enter your choice: 5
Enter the name of the contact to delete: John Doe Jr.
```

## Future Enhancements
While the current version of the application provides a basic functionality for managing contacts, there are several potential enhancements that can be considered for future development:<br>
1. **Data Persistence:** Implement a mechanism to store contacts persistently, such as using a database or file storage, allowing users to access their contacts across sessions.
2. **Graphical User Interface (GUI):** Create a user-friendly graphical interface for a more intuitive user experience.
3. **Data Validation and Error Handling:** Incorporate robust input validation and error handling mechanisms to enhance the reliability of the application.
4. **Contact Categories or Groups:** Allow users to categorize contacts into groups or categories for better organization.
5. **Import/Export Contacts:** Add features to import contacts from external sources (e.g., CSV files) and export contacts to various formats.
6. **Additional Contact Information:** Extend the Contact class to include more details like birthdate, organization, etc.
7. **User Authentication:** Implement user authentication for secure access and management of contacts.
