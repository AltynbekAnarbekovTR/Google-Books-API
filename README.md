
# Books Website using Google Books API

This a book website that was built using Vite, TypesScript, React, Redux Toolkit, react-hook-form, Vitest and React Testing Library. Google Books was used as the API since it is one of the largest book-related APIs. 

![Google Books API screenshot 1](https://user-images.githubusercontent.com/62358513/233806043-f97784ca-b9f6-4ab2-a0d0-7d9f819fd459.JPG)
<img src="https://user-images.githubusercontent.com/62358513/233806043-f97784ca-b9f6-4ab2-a0d0-7d9f819fd459.JPG" style="max-width: 200px; height: 200px;">

## Tools and libraries used 
- React with TypeScript
- Vite was chosen as a build tool since it is faster than create-react-app
- Redux Toolkit was used to store app state
- Requests to the API are made using createAsyncThunk
- Form was implemented using react-hook-form
- Tests are written using Vitest and React Testing Library. Code coverage report is shown after running tests. Code coverage is above 90%. 

## Features
On the website you can: 

- Navigate between Home, Add Book and About Us pages
- Search different books in Google Books
- On click on a card a modal window is opened showing a detailed information about the book
- Add your own book

Upcoming features: 
- You can add books to the "Favourites" tab
- Cross platform
- Apply search filters
- Light/dark mode toggle
- E2E tests using cypress

