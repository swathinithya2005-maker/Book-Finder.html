
 Book Finder

A simple and user-friendly Book Finder Web Application that allows users to search for books and view important book details using the Google Books API.

 Features

Search books by name
 Display book title
 Display author name
 Display published date
 Display book cover image
 Display a short book description
 Loading message while fetching data
 Error message for invalid searches
 Simple and responsive user interface

 Technologies Used

 **HTML5** – Structure of the web page
 **CSS3** – Styling and layout
 **JavaScript (ES6)** – Application logic and API handling
 **JSON** – Processing API response data
 **Google Books API** – Fetching book information

 API Used

This project uses the Google Books API to retrieve book information.

API Endpoint:

`https://www.googleapis.com/books/v1/volumes?q=BOOK_NAME`

The application uses JavaScript's `fetch()` method to send a request to the API and processes the returned JSON data.

 How It Works

1. Enter a book name in the search box.
2. Click the **Search** button.
3. JavaScript gets the entered book name.
4. A request is sent to the Google Books API.
5. The API returns book information in JSON format.
6. JavaScript extracts the required details.
7. The results are displayed on the web page.

The application extracts the book title, author, publication date, image, and description from the API response.

 Project Structure

```text
Book-Finder/
│
├── book finder.html
└── README.md
```
 Error Handling

The application handles different situations such as:

* Empty search input
* Book not found
* API/request errors

If the search box is empty, the application displays **"Please enter a book name"**. If no books are returned, it displays **"Book not found"**.

 Project Objective

The main objective of this project is to demonstrate how **JavaScript, APIs, JSON data, asynchronous programming, and DOM manipulation** can be used to build a practical web application.
 Future Enhancements

* Add book categories and filters
* Add pagination
* Add detailed book information
* Add favorites/wishlist feature
* Add dark mode
* Add responsive mobile design
* Add book preview links

## 👩‍💻 Author

**Book Finder Web Application**

Built using HTML, CSS, JavaScript and Google Books API.
