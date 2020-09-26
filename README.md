Part of Android Development - ISMIN 2020

Course followed by students of Mines St Etienne, ISMIN - M2 Computer Science.

[![Mines St Etienne](./logo.png)](https://www.mines-stetienne.fr/)

# TP1: Introduction to Kotlin

## 📝 Goal

The goal is to discover Kotlin and its ecosystem by implementing:

- 📙 A `Book` data class containing 3 string attributes:
  - `title`
  - `author`
  - `date`
- 📚 A `Bookshelf` class that internally store books and have the following public functions:
  - `addBook(book: Book)`
  - `getBook(title: string)` returning a `Book`
  - `getBooksOf(author: string)` returning an array of `Book`s, alpha sorted by title
  - `getAllBooks()` returning an array of `Book`s, alpha sorted by title
  - `getTotalNumberOfBooks()` returning a number

To guide you and help you find out if everything is ✅ a test suite is available in `BookshelfUnitTest.kt`.
These tests can be ran using Jest in command line or inside your IDE.

## 🚀 Getting Started

 - Start Android Studio
 - Select `Open an existing Android Studio project` and pick this directory

That's it! You can code!

## 🛰 Extra:

- Handle the `date` attribute as a Date and not a string
- Add a test, and a function `getBooksPublishedBefore(aDate: string | Date)` returning an array of `Book`s
