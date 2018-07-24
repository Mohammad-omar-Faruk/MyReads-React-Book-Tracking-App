# Project Description

This is the 7th project for Udacity Front-End Nanodegree build on top of the starter template containing a static example of what should be made interactive with React. The template was provided by Udacity.

The application allows the user to search for books, select them and add to one of three categorized bookshelfs: currently reading, want to read and read.

The user can check the basic information (like publisher, language, rating or description - if they are available) on each book using "details" button.

## Installation (How To Use)

To get started you need to have Node.js and npm installed on your computer. Then:

- Download a zipped file to your local machine from here or cloned project files 
- Decompress the app.
- Using terminal on your local machine go to the folder containing the app.
- install dependencies with `npm install`
- use command line `npm start`  to run the application in a new browser tab/window (this will start the development server). By default server runs on port 3000.
- You can now click on the plus button to search a book by title or author.
- When you find the desired book you can add it to the desired shelf.
- Returning back to your library you will find the book on the selected shelf.
- In the search page you can easily check if the book in your library and on which shelf.
- The library is divided into three shelves as mentioned up in the Project Description. You can move the book to another shelf as the status changes. For example if you finished reading a book you can move it from "Currently Reading" shelf to "Read" one.


## Note about API

The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.

## Project Dependencies

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app), so all dependencies will be automatically installed. These are:

* prop-types
* sort-by
* react-router-dom

## License:

- This project is licensed under the terms of the [MIT].
