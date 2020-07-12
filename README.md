# SimplerentFox

> ### 🦊 A Relaxed theme for Firefox completly transparent and keyboard centered.

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/Firefox.png)

#### Features:

- **Compressed** files
- **As simple as you want**: Non-Compressed files for custom rules!
- **Variables** for custom opacity and colors
- Tab bar, URLBar and Sidebar **transparent**!
- **Keyboard** Centered Design!

### Installation:

1. In the searchbar type `about:config`
2. A dialog will be shown to you and press the `I accept the risk` button.
3. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
4. Go to your Firefox profile located in `$HOME/.mozilla/firefox/XXXXXXX.default-release/`.
5. Create a folder and name it **`chrome`** (with lowercase) and then paste the `userChrome.css` and `userContent.css` (There's only one `userContent.css` ) files into it. 
6. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/)
7. E N J O Y 🦊

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/Firefox_1.png)

### Some custom preferences:

- You can choose between both files `userChrome__NoURLBar` and `userChrome__WithURLBar` . Don't forget to delete the rest of the text in the title and just have `userChrome`! 

- You can check the sections in the `no-compressed` files and make the changes you want! 

- You can use the `compressed` files if you want a simpler experience (They also have **variables** so you can change the colors)

#### Your own colors and opacity:

In this section of the code you can change the colors, it's in RGBA so you can easily change the opacity and accent color, by default it's `#eaeaea`

#### A button you need doesn't show? You can easily add them again

In this section you can comment adding `/* */` around the button you want to show. 
  

### Shortcuts!
> This userstyle was made for a keyboard centered usage, like Tilling Window Manager users or just cool people that loves them! 🤖
In this section I show you some cool shortcuts you can use with this theme for a better experience

- `Ctrl + L` It focuses on the URLBar, very useful for quick searches and bookmarks usage
- `Ctrl + B` It shows you the Bookmarks / History Bar 
- `Ctrl + T` Opens a new Tab
- `Ctrl + W` Closes a Tab
- `Ctrl + Shift + T` Re-opens a tab that you just close
- `Ctrl + R` Refresh the page you're on
- `Ctrl + Shift + A` Quick open for Add-Ons

#### Without URL Bar:

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/FirefoxWUB.png)

#### With URL Bar:

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/FirefoxCUB.png)
