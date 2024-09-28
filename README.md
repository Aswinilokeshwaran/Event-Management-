# Event-Management-
Here's an explanation of the HTML code for the "Events" page:

## HTML Structure 

### Head Section

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Events</title>
        <link rel="icon" href="date.png">
    </head>
```
- **`<!DOCTYPE html>`**: Specifies the document type as HTML5.
- **`<html>`**: Starts the HTML document.
- **`<head>`**: Contains metadata and links for the document.
  - **`<title>Events</title>`**: Sets the title of the webpage, which will be displayed in the browser tab as "Events".
  - **`<link rel="icon" href="date.png">`**: Sets the favicon (icon displayed in the browser tab) to an image named `date.png`. This image must be available in the same directory as the HTML file for it to be displayed correctly.

### Body Section

```html
<body bgcolor="black" style="color:white;">
```
- **`<body>`**: Contains all the visible content on the page.
- **`bgcolor="black"`**: Sets the background color of the body to black (this attribute is deprecated).
- **`style="color:white;"`**: Sets the default text color for the content within the body to white using inline CSS styling.

### Main Heading and Introduction

```html
<center>  
    <h1> UPCOMMING EVENTS 📆</h1>   
    <p> Don't Miss Your Event and Stay Tuned!</p>
</center>
<hr>
```
- **`<center>`**: Centers the enclosed elements on the page (this tag is deprecated and CSS should be used instead).
  - **`<h1>`**: Displays the main heading "UPCOMING EVENTS 📆".
  - **`<p>`**: Displays a short introductory paragraph: "Don't Miss Your Event and Stay Tuned!"
- **`<hr>`**: Adds a horizontal line separator, visually separating content sections.

### Event Description Paragraph

```html
<p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit...
</p>
```
- **`<p>`**: Displays a paragraph with placeholder text (`Lorem ipsum`). This text acts as a placeholder to represent content that will be provided later.

### Photo Gallery Section

```html
<center> 
    <img src="event1.png">
    <h1> Photo Gallery</h1>
    <h3> Free Entry|Free food|pets are Not allowed </h3>
</center>
```
- **`<center>`**: Centers the content in the section.
  - **`<img src="event1.png">`**: Displays an image named `event1.png`. This image must be in the same directory as the HTML file for it to be displayed.
  - **`<h1>`**: Displays a heading "Photo Gallery" below the image.
  - **`<h3>`**: Displays additional event information such as "Free Entry | Free food | Pets are Not allowed".

### Additional Event Description

```html
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit...
</p>
```
- **`<p>`**: Displays another paragraph of placeholder text, possibly providing more details or descriptions for the events.

### Fashion Store Section

```html
<center>
    <img src="event2.png">
    <h1>
        <a href="https://www.myntra.com/"> Fashion Store</a>
    </h1>
    <h3> Free Entry|Free food|pets are Not allowed </h3>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit...
    </p>
    <hr>
</center>
```
- **`<center>`**: Centers all the content within the "Fashion Store" section.
  - **`<img src="event2.png">`**: Displays an image named `event2.png`.
  - **`<h1>`**: Displays a heading labeled "Fashion Store".
    - **`<a href="https://www.myntra.com/">Fashion Store</a>`**: This heading is a clickable link that redirects to the Myntra website.
  - **`<h3>`**: Displays additional event details below the "Fashion Store" heading: "Free Entry | Free food | Pets are Not allowed".
  - **`<p>`**: Contains another paragraph with placeholder text (`Lorem ipsum`), providing more information about the fashion store event.
  - **`<hr>`**: Adds another horizontal line separator to divide content sections.

### Contact Information

```html
<center>
    <h1> Contact</h1>
    <h3> +91 59533660 | eventcollab@gmail.com</h3>
    <h6> 9th block MGR Nagar Bangalore-678345</h6>
</center>
```
- **`<center>`**: Centers the contact information section.
  - **`<h1>`**: Displays the heading "Contact".
  - **`<h3>`**: Displays a phone number and email address: "+91 59533660 | eventcollab@gmail.com".
  - **`<h6>`**: Displays the address: "9th block MGR Nagar Bangalore-678345".

### Closing Tags

```html
</body>
</html>
```
- Closes the body and HTML tags, indicating the end of the document.

## Summary of the Code
- The HTML document creates a simple event webpage with:
  - A centered main heading and introduction.
  - Placeholder paragraphs to represent descriptions or information.
  - Image sections labeled as a "Photo Gallery" and a "Fashion Store" with respective descriptions.
  - A contact section at the end of the page.
- Images (`event1.png`, `event2.png`, and `date.png`) are referenced locally, meaning they must be present in the same directory for them to display correctly.
- The use of deprecated tags like `<center>` and the `bgcolor` attribute can be replaced by modern CSS styles to improve structure and appearance.
