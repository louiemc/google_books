# google_books
## Summary
This is a React-based Google Books Search App

## Technologies Used
- MongoDB
- Express
- React
- Node
- Create React components
- Work with helper/util functions
- Utilize React lifecycle methods to query and display books based on user searches
- Node, Express, and MongoDB will be used so users can save books to review or purchase later

## What Will The App Have?
- Search: User can search for books via the Google Books API and render them here. User has the option to "View" a book, bringing them to the book on Google Books, or "Save" a book, saving it to the Mongo database
- Saved: Renders all books saved to the Mongo database. User has an option to "View" the book, bringing them to the book on Google Books, or "Delete" a book, removing it from the Mongo database

### Bonus: Live Updates to Saved Books
- Using React routing and socket.io to create a notification or component that triggers whenever a user saves a book
  - The message will include the title of the saved book
