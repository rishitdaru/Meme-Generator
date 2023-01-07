## Description

This is a Meme Generator that can be used to add text to trending meme images pulled from an API. The app can be tweaked a bit to use a specific set of images that can be specified in memesData.js

# Preview:

// add image here.

- The `public` directory contains the html page
- The `src` directory contains the images and the components folder and all other js and css files.
- The project has 2 components:
  - `Header.js`: inlcudes the header bar that displays the website title and logo
  - `Meme.js`: displays meme section where user can request random meme image, add text to it and also print the final meme
- `App.js` then collates `Navbar.js` & `Main.js` together and exports to `index.js`
- `index.js` renders the page using `style.css`.

## Installation

The dependencies required are all included in the `package.json` file. They will all be installed by running the `npm install` command.

## Set-up

To start the project run `npm start`.

## Technologies

This project was bootstrapped with create-react-app. `npx create-react-app`.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png">
  <img width="30px" alt="Shows a logo of c-sharp" src="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png">
</picture>
