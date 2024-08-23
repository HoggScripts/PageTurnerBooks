# PageTurnerBooks
Page Turner Books is a mobile application designed to help users track their reading habits, search for books, and manage their reading lists. The app includes features like barcode scanning, book search through the Google Books API, user account management, and book tracking. The project was developed using SwiftUI and Firebase for persistent data storage, following a streamlined design process that focused on essential features while ensuring a smooth user experience (UX) and consistent user interface (UI).

Key Features:

User Accounts: Users can register, sign in, sign out, change their passwords, and delete their accounts. Account information is securely managed and stored using Firebase Authentication and Firestore.
Book Search and Barcode Scanning: Users can search for books by entering text or scanning barcodes, with data retrieved from the Google Books API. The app automatically converts barcodes to ISBNs for accurate searches.
Reading Lists and Book Tracking: Users can add books to 'Want to Read,' 'Currently Reading,' and 'Finished Reading' lists. The app supports progress tracking, allowing users to log their reading status and update it as they progress through a book.
Persistent Data Storage: All user data, including book lists and tracking information, is stored in Firebase Firestore, ensuring data is saved and accessible across sessions.
User Interface and Experience: The app follows Apple's Human Interface Guidelines, ensuring a high-contrast, accessible design with consistent navigation and branding.
Design and Implementation:

UI/UX Design: The design process focused on creating a clean, intuitive interface with reusable components, such as buttons, text fields, and navigation elements. The app’s UI is consistent across different views, with a cohesive color palette and clear navigation paths.
API Integration: The Google Books API is seamlessly integrated into the app, allowing users to search for books and retrieve detailed information. The barcode scanner is a key feature that enhances the user experience by enabling quick and accurate book searches.
Database Management: Firebase Firestore was chosen for its scalability and ease of use. The database is structured using nested collections to manage user data and book lists effectively, ensuring data integrity and synchronization across devices.
Error Handling and Validation: The app includes robust error handling and validation mechanisms to prevent invalid data input and handle database errors gracefully. Users receive clear feedback and warnings when necessary, ensuring a smooth interaction with the app.
