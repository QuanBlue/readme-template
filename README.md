<h1 align="center">
  <br>
  <img src="./assets/readme-icon.png" alt="icon" width="300"></img>
  <br>
  <b>README TEMPLATE</b>
  <br>
</h1>

<h4 align="center">Summarize application.</h4>

<p align="center">
  <b>
    <a href="#demo">Demo</a> •
    <a href="#documentation">Documentation</a> •
    <a href="#usage">Usage</a> •
    <a href="#credits">Credits</a> •
    <a href="#license">License</a>
  </b>
</p>

![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/app/img/markdownify.gif)

## Demo

Check out the [**demo video**](https://www.youtube.com/channel/UCALhAytLBhmG2un43YxU4mw) to see the app in action.

## Key Features

-  LivePreview - Make changes, See changes
   -  Instantly see what your Markdown documents look like in HTML as you create them.
-  Sync Scrolling
   -  While you type, LivePreview will automatically scroll to the current location you're editing.
-  GitHub Flavored Markdown
-  Syntax highlighting
-  Dark/Light mode
-  Toolbar for basic Markdown formatting
-  Supports multiple cursors
-  Save the Markdown preview as PDF
-  Emoji support in preview :tada:
-  App will keep alive in tray for quick usage
-  Full screen mode
   -  Write distraction free.
-  Cross platform
   -  Windows, macOS and Linux ready.

## Getting start

### Prerequisites

-  Python `>= 3.10.7`

### Environment Variables

To run this project, you need to add the following environment variables to your `.env` file in `/`:

-  **App configs:**

   -  `SECRET_KEY`: a key used by Flask to encrypt and sign session data.
   -  `PORT`: specify which port the Flask application should listen on.

   Example:

   ```sh
   # .env
   SECRET_KEY="Readme-template"
   PORT=3000
   ```

### Run locally

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python](https://www.python.org/downloads/) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/QuanBlue/Readme-template

# Go into the repository
$ cd Readme-template

# Install dependencies
$ npm install

# Run the app
$ npm start
```

> **Note**
> If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Credits

This software uses the following open source packages:

-  [Electron](http://electron.atom.io/)
-  [Node.js](https://nodejs.org/)
-  [Marked - a markdown parser](https://github.com/chjj/marked)
-  [showdown](http://showdownjs.github.io/showdown/)
-  [CodeMirror](http://codemirror.net/)
-  Emojis are taken from [here](https://github.com/arvida/emoji-cheat-sheet.com)
-  [highlight.js](https://highlightjs.org/)

## License

Distributed under the MIT License. See <a href="./LICENSE">`LICENSE`</a> for more information.

---

> Bento [@quanblue](https://bento.me/quanblue) &nbsp;&middot;&nbsp;
> GitHub [@QuanBlue](https://github.com/QuanBlue) &nbsp;&middot;&nbsp; Gmail quannguyenthanh558@gmail.com
