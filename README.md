<h1 align="center">
  <img src="./assets/readme-icon.png" alt="icon" width="200"></img>
  <br>
  <b>README template</b>
</h1>

<p align="center">Summarize application.</p>

<!-- Badges -->
<p align="center">
  <a href="https://github.com/QuanBlue/Readme-template/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/QuanBlue/Readme-template" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/QuanBlue/Readme-template" alt="last update" />
  </a>
  <a href="https://github.com/QuanBlue/Readme-template/network/members">
    <img src="https://img.shields.io/github/forks/QuanBlue/Readme-template" alt="forks" />
  </a>
  <a href="https://github.com/QuanBlue/Readme-template/stargazers">
    <img src="https://img.shields.io/github/stars/QuanBlue/Readme-template" alt="stars" />
  </a>
  <a href="https://github.com/QuanBlue/Readme-template/issues/">
    <img src="https://img.shields.io/github/issues/QuanBlue/Readme-template" alt="open issues" />
  </a>
  <a href="https://github.com/QuanBlue/Readme-template/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/QuanBlue/Readme-template.svg" alt="license" />
  </a>
</p>

<p align="center">
  <b>
      <a href="#demo">Demo</a> •
      <a href="https://github.com/QuanBlue/Readme-template">Documentation</a> •
      <a href="https://github.com/QuanBlue/Readme-template/issues/">Report Bug</a> •
      <a href="https://github.com/QuanBlue/Readme-template/issues/">Request Feature</a>
  </b>
</p>

<br/>

![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/app/img/markdownify.gif)

<details open>
<summary><b>Table of Contents</b></summary>

-  [Demo](#demo)
-  [Key Features](#key-features)
-  [Getting Started](#getting-started)
   -  [Prerequisites](#prerequisites)
   -  [Environment Variables](#environment-variables)
   -  [Installation](#installation)
-  [Roadmap](#roadmap)
-  [Contributors](#contributors)
-  [Credits](#credits)
-  [License](#license)
-  [Related Projects](#related-projects)
</details>

## Demo

Check out the [**demo video**](https://www.youtube.com/channel/UCALhAytLBhmG2un43YxU4mw) to see the app in action.  
Here is deployed website: [**https://quanblue.netlify.app/**](https://quanblue.netlify.app/)

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

## Getting Started

### Prerequisites

Before proceeding with the installation and usage of this project, ensure that you have the following prerequisites in place:

-  **Python:** `>= 3.10.7`
-  **Docker Engine:** Docker provides a consistent and portable environment for running applications in containers. Install [here](https://www.docker.com/get-started/).

### Environment Variables

To run this project, you need to add the following environment variables to your `.env` file in `/`:

-  **App configs:** Create `.env` file in `./`

   -  `SECRET_KEY`: a key used by Flask to encrypt and sign session data.
   -  `PORT`: specify which port the Flask application should listen on.

   Example:

   ```sh
   # .env
   SECRET_KEY="Readme-template"
   PORT=3000
   ```

You can also check out the file `.env.example` to see all required environment variables.

> **Note**: If you want to use this example environment, you need to rename it to `.env`.

### Installation

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python](https://www.python.org/downloads/) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/QuanBlue/Readme-template

# Go into the repository
cd Readme-template

# Install dependencies
npm install

# Run the app
npm start
```

> **Note**
> If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Roadmap

-  [x] Update theme
-  [ ] Add more features

## Contributors

<a href="https://github.com/QuanBlue/Readme-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=QuanBlue/Readme-template" />
</a>

Contributions are always welcome!

## Credits

This software uses the following open source packages:

-  [Node.js](https://nodejs.org/)
-  [Marked - a markdown parser](https://github.com/chjj/marked)
-  Emojis are taken from [here](https://github.com/arvida/emoji-cheat-sheet.com)

## License

Distributed under the MIT License. See <a href="./LICENSE">`LICENSE`</a> for more information.

## Related Projects

-  <u>[**QuanBlue**](https://github.com/QuanBlue/QuanBlue)</u>: My bio
-  <u>[**Portfolio**](https://github.com/QuanBlue/Portfolio)</u>: My first portfolio website, using MERN stack. [Visit here](https://quanblue.netlify.app/)
-  <u>[**Readme-template**](https://github.com/QuanBlue/Readme-template)</u>: A template for creating README.md

---

> Bento [@quanblue](https://bento.me/quanblue) &nbsp;&middot;&nbsp;
> GitHub [@QuanBlue](https://github.com/QuanBlue) &nbsp;&middot;&nbsp; Gmail quannguyenthanh558@gmail.com
