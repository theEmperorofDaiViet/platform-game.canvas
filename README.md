<a name="readme-top"></a>
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#key-features">Key Features
      <ul>
        <li><a href="#the-game">The Game</a></li>
        <li><a href="#the-technology">The Technology</a></li>
      </ul>    
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<p align="center">
    <img src="images\cover.jpg" width="175">
</p>

# About The Project
Another version using Canvas of the original [Platfrom Game](https://github.com/theEmperorofDaiViet/platform-game). It is based on chapter 17 of the famous book about JS - "Eloquent JavaScript", with a few additional features.

## Built With
* [![HTML5][HTML5-shield]][HTML5-url]
* [![CSS3][CSS3-shield]][CSS3-url]
* [![JavaScript][JavaScript-shield]][JavaScript-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Getting Started

## Prerequisites
Before cloning and using this application, you'll need to install these things on your computer:
* [Visual Studio Code](https://code.visualstudio.com/download): You can choose any IDE or Text Editor that you want. To build a simple application like this, I recommend <b>Visual Studio Code</b>.
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): An extension for Visual Studio Code that help to launch a local development server with live reload feature for static & dynamic pages.

## Installation
You can install this application by cloning this repository into your current working directory:
```sh
git clone https://github.com/theEmperorofDaiViet/platform-game.canvas.git
```
After cloning the repository, you can open the project by Visual Studio Code.

Click to <code>Go Live</code> from the status bar to turn the server on/off.

As usual, the app should automatically open in a new tab in your browser. It runs on port 5500 by default.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Key Features

## The Game
<i>Our game looks like this:</i>
<p align="center">
    <img src="images\thegame.png" width="720">
</p>
<br/>
<table align="center">
    <tr>
        <td><img src="images\player.png" width="480"></td>
        <td>Player</td>
    </tr>
    <tr>
        <td><img src="images\sprites.png" width="104"></td>
        <td>Wall, Lava and Coin</td>
    </tr>
</table>


<p>The player's task is to collect the coins while avoiding the lava. A level is completed when all coins have been collected. A level is completed when all coins have been collected. The player starts with 5 <i>lives</i> and lose one life each time they die. When the player is out of lives, the game restarts from the beginning. You can check the player's lives at the top-right corner of the game. The empty heart is the life that the player've lost, while the filled one represents the remainder.</p>

<p>The player can walk around with the left :arrow_left: and right :arrow_right: arrow keys and can jump with the up :arrow_up: arrow. Jumping is a specialty of this game character. It can reach several times its own height and can change direction in midair. This may not be entirely realistic, but it helps give the player the feeling of being in direct control of the on-screen avatar.</p>

There are different kinds of lava:
  - <b>Normal lava:</b> lava that doesn't move
  - <b>Horizontally moving lava:</b> lava that move back and forth horizontally
  - <b>Vertically moving lava:</b> lava that move like vertically moving blobs
  - <b><i>Dripping</i> lava:</b> vertically moving lava that doesn't bounce back and forth but only moves down, jumping back to its starting position when it hits the floor.

<p>You can pause and unpause the game by pressing the <kbd>Esc</kbd> key.</p>

## The Technology

<p>We will use Canvas to display the game, and we’ll read user input by handling key events.</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Usage

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Contact

You can contact me via:
* [![GitHub][GitHub-shield]][GitHub-url]
* [![LinkedIn][LinkedIn-shield]][LinkedIn-url]
* ![Gmail][Gmail-shield]:&nbsp;<i>Khiet.To.05012001@gmail.com</i>
* [![Facebook][Facebook-shield]][Facebook-url]
* [![Twitter][Twitter-shield]][Twitter-url]

<br/>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- Tech stack -->
[HTML5-shield]: https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white
[HTML5-url]: https://www.w3.org/html/
[CSS3-shield]: https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white
[CSS3-url]: https://www.w3.org/Style/CSS/
[JavaScript-shield]: https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E
[JavaScript-url]: https://www.ecma-international.org/

<!-- Contact -->
[GitHub-shield]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[GitHub-url]: https://github.com/theEmperorofDaiViet
[LinkedIn-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[LinkedIn-url]: https://www.linkedin.com/in/khiet-to/
[Gmail-shield]: https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white
[Facebook-shield]: https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white
[Facebook-url]: https://www.facebook.com/Khiet.To.Official/
[Twitter-shield]: https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white
[Twitter-url]: https://twitter.com/KhietTo