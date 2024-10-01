# Fetching Library Data Web Application

## Overview
This web application is designed to retrieve and display library book data from an Excel sheet. The data includes information such as book title, location, authors, and edition. Built using **HTML**, **Tailwind CSS**, and **JavaScript**, the app provides a smooth search and browsing experience for users.

## Features
- **Book Search**: 
  - A search bar with fuzzy search, making it easy to find books even with partial matches or case-insensitive inputs.
  - **Voice Search**: Users can click the "Search with Voice" button and speak the book title. The recognized title will automatically be entered in the search bar, and the app will perform the search.
  
- **Suggest Book**: 
  - A "Suggest Book" button takes users to a separate page that displays 5 random books from the library's collection, along with their locations, authors, and other details.

## Technologies Used
- **HTML**: For the structure and content of the web pages.
- **Tailwind CSS**: For styling and layout.
- **JavaScript**: For adding interactive functionality and handling the data.
- **Fuzzy.js**: For implementing the fuzzy search feature, enabling case-insensitive and flexible searching.

## How to Use
1. Open the main page and use the search bar to type a book name, then press Enter or click the Search button.
2. To use voice search, click the "Search with Voice" button and speak out the book name.
3. Click "Suggest Book" to view a random selection of 5 books with their details on the next page.

## Future Enhancements
- Adding more search filters (e.g., by author or edition).
- Enhancing voice recognition for better accuracy.
- Adding options to save favorite books or suggest edits to book details.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.