Web App for Managing Books
This repository contains the source code for a simple web application that allows users to manage a list of books. The application provides features to add new books, mark them as read or unread, and delete books. The interface includes a modal for adding new books, and books are categorized into two sections: "Read" and "Unread."

Getting Started
To run the web application locally, follow these steps:

Clone the repository:

bash
Copy code
git clone [repository_url]
Open the index.html file in your preferred web browser.

Features
Adding Books: Users can add new books to the collection by filling out the form in the modal.

Mark as Read/Unread: Users can mark books as read or unread, and the books will be moved between the "Read" and "Unread" sections accordingly.

Deleting Books: Users can delete books from the collection, removing them permanently.

Code Explanation
The main functionality of the web application is implemented in JavaScript. Here are the key components of the code:

Initialization and Event Listeners
The application displays a welcome message using alert.call(window, 'Hallo, Selamat datang di web aplikasi buku');.
Event listeners are set up for the "Add Book" button and modal close button.
Constants
Constants such as UNCOMPLETED_BOOK_ID, COMPLETED_BOOK_ID, and BOOK_ITEMID are defined for identifying different elements and data.
Functions
addBook: Adds a new book to the collection and updates the storage.
makeBook: Creates the HTML structure for a book with title, author, and year.
createButton: Creates a button element with a specified class and event listener.
createReadButton, createTrashButton, createUnreadButton: Creates buttons for marking as read, deleting, and marking as unread, respectively.
addBookToCompleted, removeBookFromCompleted, undoBookFromCompleted: Functions to handle moving books between "Read" and "Unread" sections.
Event Listeners and DOMContentLoaded
Event listeners are set up for form submission, modal toggle, and modal close.
The DOMContentLoaded event is used to initialize the application and load data from storage.
Storage Handling
Functions like updateDataToStorage, loadDatafromStorage, checkStorage, and events (ondatasaved, ondataloaded) handle data storage operations.
Contributing
Feel free to contribute to the development of this web application by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!

License
This project is licensed under the MIT License.




