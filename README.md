## InventoryApp

### Overview
InventoryApp is an Android application designed to help users efficiently manage their inventory. The app enables users to add, update, delete, and track inventory items while ensuring a seamless and user-friendly experience. Built using Kotlin in Android Studio, it leverages the Room Database for local data storage. The primary goal of this app was to streamline inventory management, reducing manual effort and improving accessibility for users.

### User Needs and UI Design
This app was designed to address the need for an intuitive and efficient inventory management system. Users required a straightforward interface that allowed them to easily perform CRUD (Create, Read, Update, Delete) operations on inventory items. To support these needs, the following screens and features were implemented:
- **Home Screen:** Displays the inventory list with search functionality.
- **Add/Edit Screen:** Enables users to input or modify item details.
- **Detail View:** Provides an overview of an inventory item.
- **Delete Functionality:** Allows users to remove unwanted items.

The UI was designed with simplicity and usability in mind, incorporating clear navigation, responsive elements, and an intuitive layout. By following Material Design principles, the interface ensures accessibility and ease of use.

### Features
- **Add Inventory Items:** Users can input new inventory items with details such as name, quantity, and price.
- **Update Items:** Modify existing inventory data seamlessly.
- **Delete Items:** Remove items from the inventory.
- **View Inventory List:** Display all stored inventory items in a structured format.
- **Search Functionality:** Quickly locate items within the inventory.
- **Persistent Storage:** Uses Room Database to ensure data is stored locally.

### Development Approach
The development process involved structured planning and an iterative approach to coding. Key techniques and strategies included:
- **MVVM Architecture:** Ensured separation of concerns, making the app more maintainable and scalable.
- **Room Database Implementation:** Provided efficient local data storage and retrieval.
- **LiveData & ViewModel:** Enhanced real-time UI updates.
- **Kotlin Coroutines:** Managed background tasks efficiently to prevent UI freezing.

These strategies can be applied in future projects to ensure scalable and well-structured applications.

### Technologies Used
- **Language:** Kotlin
- **IDE:** Android Studio
- **Database:** Room Database
- **Architecture:** MVVM (Model-View-ViewModel)

### How to Use
1. Launch the app.
2. Click **Add Item** to insert a new inventory entry.
3. Use the **Edit** option to update existing items.
4. Press **Delete** to remove an inventory item.
5. Use the **Search Bar** to find specific items quickly.

### Testing and Quality Assurance
To ensure functionality and reliability, rigorous testing was conducted:
- **Unit Testing:** Validated business logic and database operations.
- **UI Testing:** Verified user interactions and screen transitions.
- **Manual Testing:** Identified usability issues and ensured a smooth user experience.

Testing is crucial for detecting bugs early, improving performance, and ensuring a polished final product. The process revealed areas for optimization, such as refining data handling and improving UI responsiveness.

### Challenges and Innovations
Throughout the development process, several challenges required innovative solutions:
- **Efficient Data Handling:** Implemented optimized queries to enhance performance.
- **Search Functionality:** Utilized LiveData for real-time search updates.
- **Database Performance:** Indexed key database fields to improve retrieval speed.

Overcoming these challenges strengthened the overall app functionality and user experience.

### Key Successes
A standout aspect of the app was the successful integration of the Room Database with MVVM architecture, demonstrating strong knowledge of Android app development principles. Additionally, implementing an intuitive and responsive UI reinforced key design and development skills.

### Future Enhancements
- **Barcode Scanning:** Streamline item entry through barcode recognition.
- **Cloud Synchronization:** Enable multi-device support and data backup.
- **User Authentication:** Enhance security and provide personalized inventory management.

### Course Information
This project was developed as part of the **Mobile Architect & Programming** class at **Southern New Hampshire University (SNHU)**.

