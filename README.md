# BooksAPI_WebDevProject2022
Google Books API web implementation with login and csv download

The Main page below has the image UI component. 
It contains the Google login component. 
Once the user logs in the icon changes to “logout”. 
On the main page/dashboard, the user can search for a book via the textbox which connects to the Google Books API.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/100385825/210451300-5249beee-1381-435c-a3a1-4df6c9b0c8c6.png">

Login completion changes the Main page display: 

<img width="468" alt="image" src="https://user-images.githubusercontent.com/100385825/210451399-b75bca24-5bf2-4604-9ba6-783459b9cd38.png">

Once logged in, the components “Dump CSV file” and “Add BookList” appear. 
User searches for a book, and the Card component accesses the Google Books API and displays search results.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/100385825/210451694-98676e13-63d3-4dc3-b1e7-68ad4400bd91.png">

When user clicks a book, they can add a book to the booklist. 
The BookList component displays the books that have been added and saved. 
Can also remove these books from the BookList, add a note, view information about the book, and review the book in the BookList component. 

<img width="468" alt="image" src="https://user-images.githubusercontent.com/100385825/210451797-6d27c2e3-01d0-4d61-bea4-5b9f0585d5b3.png">


Navigating back to the Main Page, the user can add more books to the BookList or they can export the BookList to a CSV component: 

<img width="468" alt="image" src="https://user-images.githubusercontent.com/100385825/210451840-7bc12a40-13a6-4247-9a26-2a4568ee27e1.png">

