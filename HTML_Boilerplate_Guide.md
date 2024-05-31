# HTML boilerplate

![some alt text](https://plus.unsplash.com/premium_photo-1676150789920-da4613e518e3?q=80&w=2500&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

A boilerplate in HTML is a template you will add at the start of your project. You should add this boilerplate to all of your HTML pages. To write an HTML boilerplate, you typically include the basic structure required for any HTML document.

## 1. standard HTML boilerplate:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS file -->
    <script defer src="script.js"></script> <!-- Link to external JS file -->
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

## 2. Explanation of each part of the boilerplate:

```html
<!DOCTYPE html>
```
**Declares the document type and version of HTML.**

```html
<html lang="en">
```
 **The root element of the HTML document with the language attribute set to English.**
 
 ```html
<head>
 ```
 **Contains meta-information about the document, such as its title, character set, viewport settings, and links to CSS and JavaScript files.**

```html
<meta charset="UTF-8">
```
**Specifies the character encoding for the document.**

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
**Ensures the webpage is responsive and displays correctly on all devices.**

```html
<title>Document</title>
```
**Sets the title of the webpage, which appears in the browser tab.**

```html
<link rel="stylesheet" href="styles.css">
```
**Links to an external CSS file for styling.**

```html
<script defer src="script.js"></script>
```
**Links to an external JavaScript file and defers its execution until the HTML has been fully parsed.**

```html
<body>
```
**Contains the content of the HTML document.**

> ***for more information on HTML Element and how they are used, check the MDN website [MDN docs.](https://developer.mozilla.org/en-US/docs/Web/HTML)***