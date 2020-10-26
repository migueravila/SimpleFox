<div align="center">
<h1>SimplerentFox</h1>
<b>🦊 Linux Version</b>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/preview1.png)

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

### Linux considerations

Firefox uses the GTK3 theme you have to design the menus and the colors. The theme in the screenshots will not look like yours. It can also be useful if you don't want to change a lot of code in the URL-Bar or menus.
