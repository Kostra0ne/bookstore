# OOP Bookstore

## Context

We have learned Object-Oriented Programming and how class and inheritance work in JavaScript. Now, let's apply all of the concepts we have just learned and build an OOP based approach to the book store with a lot of books in it.

## Task & Objectives

You will be working in the `solution.js` file and the tests you can reference are in the `solution.test.js` file. To check on your progress and if you are passing the tests, you can click on the "Run Tests" button. To submit your work, you should click on the "Submit" button. You will be asked to review your test and make a final submission. After you are done with the final submission, you can't resubmit afterward.

### 1. Define the classes

- Create two classes, one for the `Bookstore` and another for each `Book`. _Hint_: These two classes are not extending each other, they are just 2 separate classes.

* **Bookstore class**

  - Should receive a name to it's `name` property.
  - Should have `books` property to store the books.

* **Book class**

  - Should receive a name and the quantity.
  - Should have a `name` and `quantity` property.

### 2. Define the methods

#### Bookstore

The `Bookstore` class should have methods for:

1. Pick a book: `pickBook` method

   - Should receive a book name.
   - Should check if it exists, and if not, it should return the message: "Book not found".
   - Should check if the book is available due to the quantity of the books, and if there are no books available (quantity property equals 0), it should return the message: "Not available". If the book exists and it's available then subtract one book from the book quantity and return the book.

2. Store a book: `storeBook` method

   - Should receive a book and add it to the `books` property.

3. Show books: `showBooks` method

   - Should show every book on the console.

#### Book

The `Book` class just needs a method to change the book name:

1. Change the name: `changeName` method -

   - Should receive a new book name and set the `name` property to it.

**Good luck!**

-_Your Ironhack team_
