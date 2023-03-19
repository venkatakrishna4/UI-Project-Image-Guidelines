# UI-Project-Image-Guidelines
# Sample Project Implementation Guidelines
1. Create a folder to implement "Image Guidelines Project"
    We have created a folder named Image_Guidelines where we will implement all the implementation inside it.
    We have three sub folders inside it to separate the individual files. They are CSS, HTML, and JSON. All the sub folders contain respective files inside them.

2. We have started our project with index.html file where we will provide a search bar to search for particular Image Guidelines
    You will be given a search bar with a search button, you need to type a name inside it and you will be redirected to respective search instruction.

# Code Implementation
1. Index.html
    - It has code for search bar and search button
    - It will take the search text you have entered and stores in a variable for future use
    - It reads "redirect.json" file and compares the search text with keys inside "redirect.json"
    - All the searching is in case insensitive
    - If any key matches with the search text, respective Image Guidelines .html file will be rendered in a new page.

2. style.css
    - It has all the CSS styles that we use in .html files
    - It primarly focus on UI experience and locationing of text or images
    - This file is created for reusability of css that improves code readability in .html files

3. other html files
    - All the other html files contains individual Image Guidelines inside it
    - These files are static files and cannot be modified dynamically
    - These files will be rendered based on search text we've entered in index.html page

# Main tags used
1. 
    <html> -> Opening tag for a html file
    </html> -> Closing tag for a html file
2. 
    <head> -> head tag is used to display the header information related to that file
    We can import external css files inside this tag
3. 
    <body> -> All the body information resides inside this tag
4. 
    <div> -> Mainly used for partitioning the webpage
5. 
    <h1>, <h2>, <h3> -> Used to display the heading information
6. 
    <ul>, <li>, <ol> -> unordered lists and ordered lists (Used to display the content point wise)
7. 
    <img> -> Used to render the images
8. 
    <figure> -> Primaly used to display images and show image captions
