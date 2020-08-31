<div align="center">
<h1>SimplerentFox: 🦊 Minimalist, Simple and Keyboard Centered</h1>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/head.png)

### Index

-   [SimplerentFox](#)
    -   [Features](#features)
    -   [Installation](#installation)
    -   [Customization](#customization)
    -   [Shortcuts](#shortcuts)
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
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX
5. Create a folder and name it **`chrome`** (with lowercase) and then paste the `userChrome.css` and `userContent.css` (There should be only one `userContent.css` ) files into it.
6. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/)
7. E N J O Y 🦊

### Customization

-   You can choose between both files `userChrome__NoURLBar` and `userChrome__WithURLBar` . Don't forget to delete the rest of the text in the title and just have `userChrome`!
-   You can check the sections in the `no-compressed` files and make the changes you want!
-   You can use the `compressed` files if you want a simpler experience (They also have **variables** so you can change the colors)

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/preview1.png)

<div align="center">
<h5>Without URL Bar</h5>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/preview2.png)

<div align="center">
<h5>With URL Bar</h5>
</div>

> ### Hiding "This time, search with" URL bar message
>
> Hiding the message can give a more minimalistic URL bar. To hide the message additional search engines need to be removed, which can be done throught the _One-Click Search Engines_ option in the [Settings' Search tab](about:preferences#search).

##### Your own colors and opacity:

In this section of the code you can change the colors, it's in RGBA so you can easily change the opacity and accent color, by default it's `#eaeaea`

<p align="center">
  <img src="https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/code-1.png">
</p>

##### A button you need doesn't show? You can easily add them again

In this section you can comment adding `/* */` around the button you want to show.

<p align="center">
  <img src="https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/code-2.png">
</p>

### Shortcuts

> This userstyle was made for a keyboard centered usage, like Tilling Window Manager users or just cool people that loves them! 🤖
> In this section I show you some cool shortcuts you can use with this theme for a better experience

-   `Alt` You can access to the global menu for an extended options you need
-   `Ctrl + L` focuses the URLBar, which is very useful for quick searches and bookmarks usage
-   `Ctrl + B` shows you the Bookmarks / History Bar
-   `Ctrl + T` Opens a new Tab
-   `Ctrl + W` Closes a Tab
-   `Ctrl + Shift + T` Re-opens a tab that you just closed
-   `Ctrl + R` Refresh the page you're on
-   `Ctrl + Shift + A` Quick open for Add-Ons

### Ports

> This userstyle was made in Linux and looking for a simple and clean look for the Firefox Web browser and ports to other OS are on mind.

##### Windows port

A Simple and Keyboard Centered userstyle for Windows!

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/win.png)

In addition to the `userChrome.css` and `userContent.css` files you'll also need the `dark_additional_windows.css`, `dark_checkboxes_and_radios.css` and `dark_context_menus.css` files in your **chrome** directory

> NOTE: Transparency in Windows breakes the window behavior. You can change the colors in the variable section of the code and still add transparency, but the window manager will have some bugs with maximized firefox.
