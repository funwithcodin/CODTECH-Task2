Name: MAYUKH BANERJEE
Company: CODTECH IT SOLUTIONS
ID: CT3MTDS68
Domain: Java Programming
Duration: August 5th to November 5th, 2024
Mentor: MUZAMMIL AHMED

Overview of the Library Management System Project:
The Library Management System project is a Java-based application designed to facilitate the management of library resources, including books, magazines, and DVDs. This system provides essential functionalities for adding new items to the library, checking out and returning items, managing overdue fines, and searching for items based on various criteria such as title, author, and category. The application is designed with a graphical user interface (GUI) using Swing, making it user-friendly for both librarians and patrons.

Objectives:
1. Resource Management: To allow users to manage various types of library resources efficiently.
2. User Role Management: To implement functionalities that cater to different user roles, such as librarians (who can add or manage items) and patrons (who can check out and return items).
3. Data Persistence: To store and retrieve data effectively, enabling persistent management of library items.
4. Fine Management: To track overdue items and manage fines associated with late returns.
5. Search Functionality: To provide an intuitive search feature for users to find items quickly based on title, author, or category.
6. User-Friendly Interface: To create an accessible GUI for easy navigation and operation.

Key Activities:
1. Class Design:
Create a base class LibraryItem and derive specific classes for different types of items (Book, Magazine, DVD).
Implement attributes such as title, author, category, and checkout status.
2. Library Database Management:
Implement the LibraryDatabase class to manage a collection of LibraryItem objects.
Develop methods for adding items, incrementing/decrementing counts, and searching for items by title.
3. Graphical User Interface:
Use Swing to create a GUI that includes fields for user input and buttons for actions (add, search, check out, return, display counts).
Organize components using layout managers (GridBagLayout) for a clean presentation.
4. Event Handling:
Implement action listeners for user interactions with the GUI, ensuring that actions such as adding items and checking out books are processed correctly.
Provide user feedback through dialog boxes (using JOptionPane) to inform users of successful actions or errors.
5. Item Management Features:
Develop functionalities for checking out and returning items, including appropriate checks for item availability.
Display item counts by category and title to assist users in tracking library resources.
6. Data Persistence (Future Work):
Plan for future enhancements that include data persistence using databases or file handling to store library data permanently.

Technology Used:
Programming Language: Java
Leveraged for its robustness and rich library support, particularly for GUI applications.
Framework:
Swing: Used for building the graphical user interface, enabling user-friendly interactions.
Data Structures:
ArrayList: For dynamic management of library items.
HashMap: For maintaining counts of each item type efficiently.

Code Explanation:
The provided code implements a basic structure of the Library Management System:
1. LibraryItem Class:
Serves as the base class with properties for title, author, category, and checked-out status.
2. Derived Classes:
Book, Magazine, and DVD extend LibraryItem, allowing for polymorphism when managing different item types.
3. LibraryDatabase Class:
Maintains a list of library items and methods for adding items, searching for items by title, and counting items by type.
Displays item counts in a dialog box for user convenience.
4. LibrarySystemGUI2 Class:
Initializes the GUI and includes input fields for item properties and buttons for actions.
Uses a ButtonClickListener inner class to handle button clicks, performing actions such as adding items, searching, checking out, and returning items.
5. Main Method:
Launches the application, creating an instance of the library system GUI.

Conclusion:
The Library Management System project serves as an effective tool for managing library resources. With its user-friendly interface and functional design, it addresses essential library operations while providing room for enhancements, such as integrating persistent data storage. Future iterations could include advanced features like overdue fine calculations, role-based access controls, and more sophisticated search functionalities to improve the overall user experience.
![Captures - File Explorer 05-11-2024 23_14_29](https://github.com/user-attachments/assets/d7473bc9-56ba-4659-bb39-bbf8f96ef447)
