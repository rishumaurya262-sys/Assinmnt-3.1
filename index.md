# Assignment 3.1 — Two-Page Website with Working Links

## 1. Objective

The objective of this assignment is to create a simple two-page website using HTML and connect the pages through working navigation links.

## 2. Introduction

HTML (HyperText Markup Language) is used to create the structure of webpages. The anchor element `<a>` is used to create hyperlinks that connect one webpage to another or open an external website. In this assignment, I created a Home page and an About page with a navigation bar and an external website link.

## 3. Project Structure

Create a folder named `two-page-website` with the following files:

```text
two-page-website/
│
├── index.html
└── about.html
```

Both HTML files should be saved in the same folder so that the navigation links work correctly.

## 4. Home Page — index.html

Create a file named `index.html` and add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Website</title>
</head>
<body>

    <!-- Website Header -->
    <header>
        <h1>My Personal Website</h1>
        <p>Welcome to my first two-page website!</p>
    </header>

    <hr>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.html">Home</a> |
        <a href="about.html">About</a>
    </nav>

    <hr>

    <!-- Main Content -->
    <main>
        <h2>Welcome to the Home Page</h2>

        <p>
            Hello! I am a student learning HTML and web development.
            This website is created as part of my HTML assignment.
        </p>

        <p>
            Here, you can learn about my interests and my journey
            into web development.
        </p>

        <h3>Useful External Website</h3>

        <p>
            Visit
            <a href="https://www.w3schools.com/"
               target="_blank"
               rel="noopener noreferrer">
                W3Schools
            </a>
            to learn more about HTML and web development.
        </p>
    </main>

    <hr>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 My Personal Website</p>
    </footer>

</body>
</html>
```

## 5. About Page — about.html

Create another file named `about.html` in the same folder and add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - My Website</title>
</head>
<body>

    <!-- Website Header -->
    <header>
        <h1>About Me</h1>
        <p>Learn more about me and my interests.</p>
    </header>

    <hr>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.html">Home</a> |
        <a href="about.html">About</a>
    </nav>

    <hr>

    <!-- Main Content -->
    <main>
        <h2>Who Am I?</h2>

        <p>
            My name is Your Name. I am a student interested in
            computers, programming, and modern technology.
        </p>

        <h2>My Education</h2>

        <p>
            I am learning technical subjects and developing my
            knowledge of web development.
        </p>

        <h2>My Hobbies</h2>

        <ul>
            <li>Learning new technologies</li>
            <li>Practicing HTML</li>
            <li>Exploring computers</li>
            <li>Improving my programming skills</li>
        </ul>

        <p>
            <a href="index.html">Return to Home Page</a>
        </p>
    </main>

    <hr>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 My Personal Website</p>
    </footer>

</body>
</html>
```

Replace `Your Name` with your actual name before submitting.

## 6. Explanation of Important HTML Elements

| Element or Attribute | Purpose |
|---|---|
| `<a href="index.html">` | Opens the Home page. |
| `<a href="about.html">` | Opens the About page. |
| `<nav>` | Groups the website navigation links. |
| `<header>` | Contains the page heading and introduction. |
| `<main>` | Contains the main content of the page. |
| `<footer>` | Displays the footer information. |
| `target="_blank"` | Opens the external website in a new tab. |
| `rel="noopener noreferrer"` | Adds security and privacy protections to the new-tab link. |

## 7. How to Run and Test the Website

1. Open Visual Studio Code.
2. Create the `two-page-website` folder.
3. Create both `index.html` and `about.html` inside it.
4. Copy the appropriate code into each file and save them.
5. Open `index.html` in Google Chrome.
6. Click the **About** link and verify that the About page opens.
7. Click **Home** on the About page and verify that you return to the Home page.
8. Click the **W3Schools** link and verify that the external website opens in a new browser tab.

## 8. Screenshot for Submission

Take a screenshot of the working website:

1. Open `index.html` in Chrome and show the Home page with the navigation links.
2. Click **About** and capture the About page as well.
3. Press `Windows + Shift + S` to take each screenshot.
4. Save the screenshots as:
   - `Assignment-3.1-Home.png`
   - `Assignment-3.1-About.png`

Submit both HTML files and the screenshots to your GitHub repository.

## 9. Conclusion

In this assignment, I learned how to create a two-page website using HTML. I used anchor elements to connect the Home and About pages, created a navigation bar, and added an external website link that opens in a new tab securely. This assignment helped me understand how hyperlinks make websites easier to navigate.

