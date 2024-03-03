# Search

A front-end for Google Search, Google Image Search, and Google Advanced Search.

This was Project 0 of HarvardX's CS50w course, and served as a quick refresher on working with HTML forms and styling using Css.

## Table of Contents

- [Search](#search)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Deploy](#deploy)
  - [Specification](#specification)

## Installation


To install and set up the project, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/GabrielMensi/cs50web-search.git
```

2.  Navigate to the project directory:
```bash
`cd cs50web-search` 
```

3.  Open the desired HTML file (e.g., `index.html`, `image-search.html`, `advanced-search.html`) using your preferred web browser.
    
4.  Explore the various features of the Google Search, Google Image Search, and Google Advanced Search pages.

## Usage

 This project is a simple front-end for Google Search, Google Image Search, and Google Advanced Search. Here's how to use it:

-   **Google Search:**   
    1.  Open `index.html`.
    2.  Type your query in the search bar.
    3.  Click the "Google Search" button to view the search results.
 
-   **Google Image Search:**
    1.  Open `image-search.html` or navigate to it from the "Image Search" link on the `index.html` page.
    2.  Enter your image search query.
    3.  Click the search button to view the Google Image search results.

-   **Google Advanced Search:**    
    1.  Open `advanced-search.html` or navigate to it from the "Advanced Search" link on the `index.html` page.
    2.  Provide input for the specified fields, including "all these words," "this exact word or phrase," "any of these words," and "none of these words."
    3.  Click the "Advanced Search" button to see the search results based on your input.

Feel free to explore the different functionalities and styles implemented in each HTML file.

Instructions on how to use the project and any relevant examples.

## Deploy

You can see the project deployment [here](https://cs50web-search.vercel.app/)

## Specification

Your website must meet the following requirements:

- [x]  Your website should have at least three pages: one for regular Google Search (which must be called  `index.html`), one for Google Image Search, and one for Google Advanced Search.
    - [x]  On the Google Search page, there should be links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there should be a link in the upper-right to go back to Google Search.
  
- [x]   On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page.
    - [x]  Like Google’s own, your search bar should be centered with rounded corners. The search button should also be centered, and should be beneath the search bar.

- [x]   On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
- [x]   On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own  [advanced search](https://www.google.com/advanced_search)  options)
    - [x]  Find pages with… “all these words:”
    - [x] Find pages with… “this exact word or phrase:”
    - [x]  Find pages with… “any of these words:”
    - [x]  Find pages with… “none of these words:”

- [x]  Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
    - [x]   Consistent with Google’s own CSS, the “Advanced Search” button should be blue with white text.
    - [x]  When the “Advanced Search” button is clicked, the user should be taken to the search results page for their given query.

- [x]  Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page.
    - [x]  You may encounter a redirect notice when using the “I’m Feeling Lucky” button. Not to worry! This is an expected consequence of a security feature implemented by Google.

- [x]  The CSS you write should resemble Google’s own aesthetics.
