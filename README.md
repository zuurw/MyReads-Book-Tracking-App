
<p align="center">
  <img width="400" height="136,038 " src="https://user-images.githubusercontent.com/40801473/43848833-c71236da-9b2b-11e8-9a03-ae1df32087de.png">
</p>


# Project Overview

MyReads: A Book Tracking App is a React.js app which allows to add books and move them into different shelves, depending on the user action.
There are 3 shelves available, corresponding to different labels: 

* Currently Reading
* Want To Read
* Read

Each book comes with a drop-down menu which contains the shelves. Clicking on the desired option moves the book to the corresponding shelf. There is also a fourth option, "none", which simply removes the book from the page.

![MyReads App Screenshot](https://github.com/DownTheMatrix/MyReads-Book-Tracking-App/blob/master/Screenshot.png?raw=true)

## How To Run The App

To get started:

* clone the project or download it as a .zip file
* open the terminal
* cd into the project folder
* install all project dependencies with `npm install`
* start the development server with `npm start`

## Search Terms

The backend API uses a fixed set of cached search results and is limited to a particular set of search terms. Here they are: 

'Android', 'Art', 'Artificial Intelligence', 'Astronomy', 'Austen', 'Baseball', 'Basketball', 'Bhagat', 'Biography', 'Brief', 'Business', 'Camus', 'Cervantes', 'Christie', 'Classics', 'Comics', 'Cook', 'Cricket', 'Cycling', 'Desai', 'Design', 'Development', 'Digital Marketing', 'Drama', 'Drawing', 'Dumas', 'Education', 'Everything', 'Fantasy', 'Film', 'Finance', 'First', 'Fitness', 'Football', 'Future', 'Games', 'Gandhi', 'Homer', 'Horror', 'Hugo', 'Ibsen', 'Journey', 'Kafka', 'King', 'Lahiri', 'Larsson', 'Learn', 'Literary Fiction', 'Make', 'Manage', 'Marquez', 'Money', 'Mystery', 'Negotiate', 'Painting', 'Philosophy', 'Photography', 'Poetry', 'Production', 'Programming', 'React', 'Redux', 'River', 'Robotics', 'Rowling', 'Satire', 'Science Fiction', 'Shakespeare', 'Singh', 'Swimming', 'Tale', 'Thrun', 'Time', 'Tolstoy', 'Travel', 'Ultimate', 'Virtual Reality', 'Web Development', 'iOS'

For the full list of terms, see the [SEARCH_TERMS.md](SEARCH_TERMS.md) file in this repo.

## Create React App

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). You can find more information on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Contributing

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This app is released under a MIT license.

## Todos

1. Add fallback images for unavailable books
2. Add starting modal with the instructions on how to use the app
3. Implement animations (spinners, etc.)
4. Add accessibility features
5. Improve performance metrics (Chrome Lighthouse)
6. Make it a progressive web app (add offline capabilities)
7. Trigger a popup box signaling that a book has been moved to the corresponding shelf
