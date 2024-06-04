# GPA Calculator

This project is a GPA Calculator web application that allows users to calculate their grade point average and keep track of their academic performance. The application includes features such as grade input, GPA calculation, and a personalized dashboard.

## Table of Contents

- [Features](#features)
- [HTML Structure](#html-structure)
- [CSS Styling](#css-styling)
- [How to Use](#how-to-use)


## Features

- **Grade Input**: Easily enter course grades, including credits and grades for each class.
- **GPA Calculation**: Automatically calculates the cumulative GPA based on the grades and credits provided.
- **Personalized Dashboard**: View GPA history, set goals, and monitor academic progress over time.

## HTML Structure

The HTML file (`index.html`) includes the following sections:

1. **Header**: Contains the navigation bar with links to different sections of the page.
2. **Introduction**: Features a cover image and a brief introduction to the app with a call-to-action button.
3. **Features**: Describes the key features of the app.
4. **About**: Provides information about the app and the development team.
5. **About Me**: Details about the developer.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GPA Calculator</title>
    <link rel="stylesheet" href="style.css" />
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="/images/apple-touch-icon.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="/images/favicon-32x32.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="16x16"
      href="/images/favicon-16x16.png"
    />
    <link rel="manifest" href="/site.webmanifest" />
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#features">Features</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#about-me">About Me</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="introduction">
        <div class="cover-image">
          <img
            src="./images/cover-image.jpg"
            height="400px"
            alt="GPA Calculator Cover Image"
          />
        </div>
        <div class="has-opacity">
          <h1>GPA Calculator</h1>
          <p>
            This intuitive tool allows you to easily calculate your grade point
            average and keep track of your academic performance with ease.
          </p>
          <a href="#" class="cta">Launch App</a>
          <a
            href="https://play.google.com/store/apps/details?id=com.gpa.calculator"
            class="download-btn"
          >
            <img
              src="./icons/google-play.png"
              class="icon-img"
              alt="Google Play Store"
            />
            Google Play Store
          </a>
        </div>
      </section>

      <section id="features">
        <h2>Key Features</h2>
        <div class="feature">
          <img src="grade-input.png" alt="Grade Input" />
          <h3>Grade Input</h3>
          <p>
            Easily enter your course grades, including credits and grades for
            each class.
          </p>
        </div>
        <div class="feature">
          <img src="gpa-calculation.png" alt="GPA Calculation" />
          <h3>GPA Calculation</h3>
          <p>
            The app automatically calculates your cumulative GPA based on the
            grades and credits you've provided.
          </p>
        </div>
        <div class="feature">
          <img src="dashboard.png" alt="Personalized Dashboard" />
          <h3>Personalized Dashboard</h3>
          <p>
            View your GPA history, set goals, and monitor your academic progress
            over time.
          </p>
        </div>
      </section>

      <section id="about">
        <h2>About the App</h2>
        <p>
          Our GPA Calculator app was developed by a team of Holberton School
          students who wanted to create a tool to help their fellow students
          stay on top of their academic performance.
        </p>
        <h3>Project Team</h3>
        <ul>
          <li>
            <a
              _blank
              href="https://www.linkedin.com/in/peter-innocent?utm_source=share&utm_campaign=share_via&utm_content=profile"
              >[Team Member 1 Name]</a
            >
            | <a _blank href="[Team Member 1 GitHub]">GitHub</a> |
            <a _blank href="[Team Member 1 Twitter]">Twitter</a>
          </li>
        </ul>
      </section>

      <section id="about-me">
        <h2>About Me</h2>
        <p>My name is Innocent Peter (Ip)</p>
        <p>
          I'm a full-stack JavaScript developer with experience in TypeScript,
          Python, and PHP.
        </p>
        <p>
          I specialize in using Nuxt.js for Vue.js, Next.js for React, Djongo
          for Python, and Laravel for PHP.
        </p>
        <p>
          I'm passionate about creating robust and scalable web applications.
        </p>
      </section>
    </main>

    <footer>
      <p>&copy; 2023 GPA Calculator. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```
