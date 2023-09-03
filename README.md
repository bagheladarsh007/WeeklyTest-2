# WeeklyTest-2
Welcome to the Jordan Shoes Online Store! This is a simple HTML/CSS template for an online store selling Jordan shoes.
Below, you'll find information on how to set up and customize this template for your own use.

## Screenshots and Explanations
## HTML Tags Explanation

This README provides an explanation of the HTML tags used in the HTML file provided.

### `<!DOCTYPE html>`

- The `<!DOCTYPE html>` declaration defines the document type and version of HTML being used, in this case, HTML5.

### `<html>`

- The `<html>` element is the root element of an HTML document. It encapsulates the entire document.

### `<head>`

- The `<head>` element contains metadata about the document, such as character encoding, viewport settings, and links to external resources.

### `<meta>`

- The `<meta>` elements provide metadata about the document. In this document:
  - `charset` specifies the character encoding as UTF-8.
  - `name="viewport"` sets the viewport settings for responsive design.

### `<link>`

- The `<link>` element is used to link an external stylesheet (`style.css`) to the HTML document to style its content.

### `<title>`

- The `<title>` element sets the title of the web page, which appears in the browser's title bar or tab.

### `<body>`

- The `<body>` element contains the main content of the web page, including text, images, and other elements.

### `<div>`

- The `<div>` element is a container for grouping and styling content. It is often used for layout purposes.

### `<nav>`

- The `<nav>` element defines a navigation section of the webpage. It contains links and navigation-related content.

### `<h3>` and `<h5>`

- The `<h3>` and `<h5>` elements are headings of different levels. They represent different levels of importance and structure within the content.

### `<input>`

- The `<input>` element creates an input field, typically used for user input, in this case, a search bar.

### `<span>`

- The `<span>` element is an inline container that can be used to apply styles or JavaScript to a specific portion of text.

### `<main>`

- The `<main>` element represents the main content of the document. It should only appear once in an HTML document.

### `<img>`

- The `<img>` element is used to display images. It includes attributes for the image source, alt text, width, and height.

### `<p>`

- The `<p>` element represents a paragraph of text within the document.

### `<footer>`

- The `<footer>` element defines the footer section of the webpage. It often contains information about the author, copyright, or related links.

### `<h1>`

- The `<h1>` element is a top-level heading, typically used for the main title of a section or page.

These are the main HTML tags used in the provided HTML file. Each tag serves a specific purpose in structuring and styling the webpage content.


## Structure of Webpage 

![webpage](https://github.com/bagheladarsh007/WeeklyTest-2/assets/142333682/613f25fb-fa1a-4089-be0e-a97af5469fc2)


## CSS Styles Explanation

This README provides an explanation of the CSS styles used in the provided CSS code.

### Universal Selector `*`

- `*` selects all elements on the page and applies the following styles:
  - `color: #fff;` sets the text color to white.
  - `margin: 0;` removes margin for all elements.
  - `box-sizing: border-box;` ensures that padding and borders do not affect the element's total width.

### `body`

- `body` styles are applied to the entire page:
  - `display: flex;` makes the body a flex container.
  - `flex-direction: column;` arranges flex children in a column layout.

### `.banner`

- Styles for the banner element:
  - `background-image` creates a gradient background.
  - `padding: 10px;` adds padding inside the banner.
  - `text-align: center;` centers text horizontally.

### `nav`

- Styles for the navigation element:
  - `background-color` sets the background color to black.
  - `padding: 15px 0;` adds padding to the top and bottom.
  - `position: sticky;` makes the navigation bar stick to the top.
  - `top: 0;` sticks the navigation bar to the top of the viewport.
  - `text-align: center;` centers the navigation items.
  - `z-index: 1;` ensures the navigation bar appears above other elements.

### `nav > h5`

- Styles for the navigation links (`h5`) within the `nav` element:
  - `display: inline-block;` arranges links horizontally.
  - `margin: 0 15px;` adds margin to separate links.

### `input`

- Styles for the input element:
  - `width: 30%;` sets the input width to 30% of its container.
  - `border: none;` removes the border.
  - `font-size: 18px;` sets the font size.

### `main`

- Styles for the main content area:
  - `background-image` sets a background image.
  - `background-size`, `background-position`, and `background-repeat` control the background image appearance.
  - `padding: 6% 10%;` adds padding to the main content.
  - `font-size: larger;` increases the font size.

### `.offer`

- Styles for the offer section:
  - `width: 70%;` sets the width of the offer section.
  - `padding: 2%;` adds padding inside the section.
  - `background-color` creates a semi-transparent black background.

### `.trending`

- Styles for the trending section:
  - `padding: 1% 5%;` adds padding inside the section.
  - `background-color` creates a semi-transparent black background.

### `.box`

- Styles for boxes within the trending section:
  - `background-color` creates a semi-transparent black background.
  - `padding: 1%;` adds padding inside the box.
  - `margin: 10px 0;` adds margin around the boxes.

### `.box > h2`

- Styles for headings within the boxes:
  - `color: rgba(0, 0, 0, 0.7);` sets the text color with some transparency.

### `.shoe`

- Styles for shoe elements within the trending section:
  - `height` and `width` set the dimensions.
  - `display: inline-block;` arranges shoes horizontally.
  - `background-color` creates a semi-transparent black background.
  - `padding: 0.1%;` adds slight padding.

### `footer`

- Styles for the footer:
  - `background-image` creates a gradient background.
  - `position: relative;` allows for absolute positioning of child elements.
  - `overflow: hidden;` hides overflowing content.
  - `width: 100%; height: 100vh;` sets the footer's size.

### `.footer-box`

- Styles for the footer content box:
  - `height: 75%; width: 85%;` sets the size and proportions of the content box.
  - `margin: 7.5%;` adds margin around the content box.
  - `box-shadow` adds a shadow to the content box.
  - `background-image` creates a gradient background.
  - `padding: 2%;` adds padding inside the content box.

### `.text-box`

- Styles for the text content within the footer:
  - `max-width: 40%;` limits the text content width.
  - `> h1` and `> p` apply styles to headings and paragraphs within the text box.

### `.image-box > img`

- Styles for the image within the footer:
  - `position: absolute;` allows for precise positioning.
  - `height`, `width`, and `border-radius` set image size and shape.
  - `right` and `top` position the image.
  - `box-shadow` adds a shadow to the image.
  - `:hover` styles apply when hovering over the image, increasing its size.

These are the CSS styles used in the provided CSS code. Each style rule defines how specific elements in the HTML file should be displayed and styled.

