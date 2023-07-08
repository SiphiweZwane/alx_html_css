# HTML Advanced Project

## Description

This README file provides a brief overview of HTML and how it's used. HTML is the standard markup language used for creating web pages. It defines the structure and content of a webpage by using various tags and elements.

## To Get Started
To start using HTML, you do not need any specific software or tools. All you need is a text editor like Notepad (Windows), Visual Studio Code or TextEdit.

## How to create HTML File
To create an HTML file, follow these steps:

1. Open your preferred text editor.
2. Create a new file.
3. Save the file with a `.html` extension (e.g., `index.html`).

## The Basic Structure of an HTML File
An HTML file follows a specific structure called the Document Object Model (DOM). Here's a basic template:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Your Page Title</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

- `<!DOCTYPE html>`: This declaration specifies that the document type is HTML5.
- `<html>`: The root element of an HTML page.
- `<head>`: Contains metadata about the document, such as the page title.
- `<title>`: Sets the title displayed in the browser's title bar or tab.
- `<body>`: Contains the visible content of the webpage.

## Adding Content
Within the `<body>` tag, you can add various HTML elements to structure and format your content. Some common elements include:

- Headings: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
- Paragraphs: `<p>`
- Links: `<a>`
- Images: `<img>`
- Lists: `<ul>`, `<ol>`, `<li>`
- Tables: `<table>`, `<tr>`, `<td>`
- Forms: `<form>`, `<input>`, `<button>`

## Adding Styles
HTML allows you to add styles to your elements using CSS (Cascading Style Sheets). You can include CSS styles internally within the HTML file or link to an external CSS file.

### Internal Styles
To add internal styles, insert a `<style>` element within the `<head>` section of your HTML file. For example:

```html
<head>
    <style>
        h1 {
            color: blue;
        }
    </style>
</head>
```

### External Styles
To link an external CSS file, use the `<link>` element within the `<head>` section. For example:

```html
<head>
    <link rel="stylesheet" href="styles.css">
</head>
```

## Previewing an HTML File
To preview your HTML file in a web browser, follow these steps:

1. Save your HTML file.
2. Double-click the file, and it will open in your default web browser.

## Author:Siphiwe Zwane

## Conclusion
This README provided a basic introduction to HTML and its usage. It covered creating an HTML file, the structure of an HTML document, adding content and styles, and previewing the HTML file in a web browser.

