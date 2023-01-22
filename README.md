# Backend Engineer Assignment

The owl library needs your help. They have recently been getting requests from the good people on internet to borrow books via a REST API service. Your mission should you choose to accept is to build this service and help spread the knowledge confined within the owl library.

The library has three kinds of books

- Paperbacks
- Hardcover
- Handmade

Each book has a title, author and a unique owl id using which anyone can query for the books availability. Due to economic constraints, there is only one book for a combination of title and author.  Once a book has been borrowed by a user, they cannot borrow it back for a period of 3 months which starts from the day they borrowed the book. Every book is returned to the library within 14 days.

The library contains books from all kinds of authors. There are certain authors which are very popular and the owl library allows you to borrow books from these authors only once in 6 months. The name for all of these authors start with the letter J.

Given the above, your mission is to develop a REST api service which helps people do the following:

- Get all the available books
- Get all books by a author
- Borrow a book
- Return a book

### Bonus:

- Given a user identifier (email or username) and a book’s unique owl id, tell the user when they will be able to borrow that book.

### Some other pointers:

- You can choose to build this in any stack of your choice.
- Please make sure to version control your code using git.
- We will be looking at how often you committed code, the structure of your code, tests and the documentation.

Please fork this repository and send us the link to your fork.
