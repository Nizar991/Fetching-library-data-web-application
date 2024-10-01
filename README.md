# Fetching Library Data Web Application

## Overview
This web application is designed to help users retrieve and view library book data stored in an Excel sheet, including details such as title, location, authors, and edition. The app is built using **HTML**, **Tailwind CSS**, and **JavaScript** with **Fuzzy.js** and **Web Speech API** for enhanced user interaction and search capabilities. It offers an easy way to search for books by typing or using voice commands and provides suggestions for random books.

## Features
- **Search Functionality**:
  - A search bar that utilizes **Fuzzy.js** for fuzzy searching, allowing partial matches and case-insensitive inputs.
  - Users can search by pressing the **Search** button or hitting the **Enter** key.
  - The **Search with Voice** feature, built using the **Web Speech API**, allows users to search for books by speaking. The recognized book title automatically populates the search bar and triggers the search.

- **Suggest Book**:
  - The "Suggest Book" button takes users to a separate page, displaying 5 random books from the library's Excel sheet along with their locations, authors, and other information.

## Project Structure
- **HTML**: Provides the structure for the web pages.
- **Tailwind CSS**: Used for styling the web pages with utility-first classes.
- **JavaScript**: Manages search functions, voice recognition, and navigation.
  - **Fuzzy.js**: Implements fuzzy search, enabling flexible matches.
  - **Web Speech API**: Handles speech recognition for voice-based searches.

## How to Use
1. On the main page, type in a book name and either press Enter or click the **Search** button to find the book.
2. For voice-based search, click the **Search with Voice** button and speak the book's name. The app will automatically search for the recognized title.
3. Click the **Suggest Book** button to view 5 random book suggestions on the next page, complete with their details.