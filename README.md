# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
 Here's a well-structured, semantically correct HTML5 document. This template includes all the essential sections and uses semantic HTML elements like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A well-structured, semantically correct HTML5 document template." />
  <title>Semantic HTML5 Template</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <header>
    <h1>My Website</h1>
    <nav>
      <ul>
        <li><a href="#home" aria-current="page">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home">
      <h2>Welcome</h2>
      <p>This is a basic HTML5 template using semantic elements for better structure and accessibility.</p>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>Learn more about our mission and values.</p>
    </section>

    <section id="blog">
      <h2>Latest Articles</h2>
      <article>
        <h3>Understanding Semantic HTML</h3>
        <p>Semantic HTML helps improve accessibility, SEO, and code clarity.</p>
        <p><time datetime="2025-04-14">April 14, 2025</time></p>
      </article>
      <article>
        <h3>Building Responsive Layouts</h3>
        <p>Discover tips and techniques for creating flexible and responsive designs.</p>
        <p><time datetime="2025-04-10">April 10, 2025</time></p>
      </article>
    </section>

    <aside>
      <h2>Related Links</h2>
      <ul>
        <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML">MDN Web Docs</a></li>
        <li><a href="https://www.w3.org/TR/html52/">W3C HTML5 Specification</a></li>
      </ul>
    </aside>
  </main>

  <footer>
    <p>&copy; 2025 My Website. All rights reserved.</p>
    <p><a href="#privacy-policy">Privacy Policy</a></p>
  </footer>

</body>
</html>
