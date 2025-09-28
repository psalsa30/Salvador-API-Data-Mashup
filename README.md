# Salvador-API-Data-Mashup
API Data Mashup for ITMGT 45.03 ECOMMERCE FUNDAMENTALS
1. Project description: 
A single-file web app that takes in an ISBN (International Standard Book Number) from a user and fetches book data from two public APIs. It shows the book title and author from both APIs as well as what genre of book it is.

2. APIs used (with links):
Open Library - https://openlibrary.org/developers/api
Google Books API - https://developers.google.com/books/docs/v1/using

3. How to set up and run locally:
  - Save supplied html as index.html in a folder
  - Open in VS Code and open with a live server
  - Enter the ISBN of the book you want to find

4. How the data join works (with a short example)
From the ISBN input of the user, it fetches data from both APIs and extracts the different categories needed (title, author, genre)

5. Known limitations
  - Limited data since both APIs which proves useful for a book finder like this
  - Both APIs have usage limits and may hit quotas
  - Titles and authors between the two APIs have a slight chance to differ and not be consistent with one another

6. AI usage note (if applicable)
  - Code suggestions for API portion
  - Debugging when I'm stuck on an error
