<div align="center">
<h1>SimplerentFox</h1>
<b>🦊 Minimalist, Simple and Keyboard Centered</b>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/WithoutURLBar.png)

### Index

-   [SimplerentFox](#)
    -   [Features](#features)
    -   [Installation](#installation)
    -   [Customization](#customization)
         - [All Versions](#three-versions)
         - [Own Colors and Opacity](#your-own-colors-and-opacity)
         - [Show buttons](#a-button-you-need-doesnt-show-you-can-easily-add-them-again)
    -   [Usage](#usage)
    -   [Startpage](#startpage)
    -   [Ports](#ports)

### Features

-   **Compressed** files
-   **As simple as you want**: Non-Compressed files for custom rules!
-   **Variables** for custom opacity and colors
-   Tab bar, URLBar and Sidebar **transparent**!
-   **Keyboard** Centered Design!

### Installation

1. In the searchbar type `about:config`
2. A dialog will be shown to you. Press the `I accept the risk` button.
3. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
4. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
5. Create a folder and name it **`chrome`** (with lowercase) and then paste the `userChrome.css` and `userContent.css`
6. You can choose between the three versions: **NoURLBar**, **WithURLBar** and **OneLine** and them compressed files, once you choose your version (You can see them here: [Versions](#three-versions)) and rename the file you choose into `userChrome.css` 
7. Then paste the `userChrome.css` and the `userContent.css` files into the folder
8. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/)
 
> E N J O Y 🦊

### Customization

-   You can choose between both files `userChrome__NoURLBar`, `userChrome__WithURLBar` and `userChrome__OneLine` . Don't forget to delete the rest of the text in the title and just have `userChrome`!
-   You can check the sections in the `no-compressed` files and make the changes you want!
-   You can use the `compressed` files if you want a simpler experience (They also have **variables** so you can change the colors)

##### Three Versions

SimplerentFox has three central versions:

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/WithoutURLBar.png)

<div align="center">
<h5>Without URL Bar</h5>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/WithURLBar.png)

<div align="center">
<h5>With URL Bar</h5>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/OneLine.png)

<div align="center">
<h5>One Line</h5>
<b>(Testing)</b>
</div>

> ### Hiding "This time, search with" URL bar message
>
> Hiding the message can give a more minimalistic URL bar. To hide the message additional search engines need to be removed, which can be done throught the _One-Click Search Engines_ option in the [Settings' Search tab](about:preferences#search).

##### Your own colors and opacity:

In this section of the code you can change the colors, it's in RGBA so you can easily change the opacity and accent color, by default it's `#186efd60`

<p align="center">
  <img src="https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/code-1.png">
</p>

##### A button you need doesn't show? You can easily add them again

In this section you can comment adding `/* */` around the button you want to show.

<p align="center">
  <img src="https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/code-2.png">
</p>

### Usage

> This userstyle was made for a keyboard centered usage, like Tilling Window Manager users or just cool people that loves them! 🤖
> In this section I show you some cool shortcuts you can use with this theme for a better experience

-   `Alt` You can access to the global menu for an extended options you need
-   `Alt + Left Arrow` You can go Back
-   `Alt + Right Arrow` You can go Forward
-   `Ctrl + L` focuses the URLBar, which is very useful for quick searches and bookmarks usage
-   `Ctrl + B` shows you the Bookmarks 
-   `Ctrl + H` shows you the History Bar
-   `Ctrl + T` Opens a new Tab
-   `Ctrl + W` Closes a Tab
-   `Ctrl + Shift + T` Re-opens a tab that you just closed
-   `Ctrl + R` Refresh the page you're on
-   `Ctrl + Shift + A` Quick open for Add-Ons

### Startpage

If anyone has the doubt, in almost all of the screenshots you can see a Startpage made for it. It's called [Bento 🍱](https://github.com/MiguelRAvila/Bento) and It's another project I made. It fits with the Firefox theme because It's done with the same principles: Minimalist, Simple and Elegant.

<p align="center">
  <img src="https://github.com/MiguelRAvila/Bento/blob/master/assets/preview.gif">
</p>

In the repo I have all the steps for you to use it!

### Ports

> This userstyle was made in Linux and looking for a simple and clean look for the Firefox Web browser and ports to other OS are on mind.

##### Windows port

A Simple and Keyboard Centered userstyle for Windows!

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/win.png)

In addition to the `userChrome.css` and `userContent.css` files you'll also need the `dark_additional_windows.css`, `dark_checkboxes_and_radios.css` and `dark_context_menus.css` files in your **chrome** directory

> ### Transparency Note
>
> Transparency in Windows breakes the window behavior. You can change the colors in the variable section of the code and still add transparency, but the window manager will have some bugs with maximized firefox.
