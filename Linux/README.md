<div align="center">
<h1>SimplerentFox</h1>
<b>🦊 Linux Version</b>
</div>

![](../Images/Header.png)

## Installation

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
4. Create a folder and name it **`chrome`** (with lowercase).
5. 5. You can choose between the three versions: **HideURLBar**, **WithURLBar** and **OneLine** (You can see them here: [Versions](#three-versions)). Once you choose your version  and rename the file you choose into `userChrome.css` 
6. Then paste the `userChrome.css` and the `userContent.css` files into the folder
7. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/)
 
> E N J O Y 🦊

### Linux considerations

Firefox uses the GTK3 theme you have to design the menus and the colors. The theme in the screenshots will not look like yours. It can also be useful if you don't want to change a lot of code in the URL-Bar or menus. You can find a lot of GTK themes [here](https://www.pling.com/browse/cat/135/order/latest/)