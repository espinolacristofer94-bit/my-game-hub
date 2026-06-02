# My Arcade Hub

Welcome to my custom arcade project! This is a simple, lightweight web portal designed to host and link to open-source browser games. 

Built using HTML5 and CSS, this project is hosted entirely for free via **GitHub Pages**.

## Features
* **Responsive Grid:** Automatically adjusts layout for different screen sizes.
* **Custom Styling:** Clean, dark-mode design with smooth hover animations.
* **Open Source:** Easy to add new games by editing the `index.html` file.

## How to Customize
To add your own games to this site:
1. Open the `index.html` file.
2. Locate the `<div class="grid">` section.
3. Add a new anchor tag with your game link:
   ```html
   <a href="URL_TO_GAME" target="_blank" class="card">
       Game Name
   </a>
