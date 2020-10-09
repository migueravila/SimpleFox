<div align="center">
<h1>SimplerentFox: 🦊 Linux Version</h1>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/win.png)

### Installation

1. In the searchbar type `about:config`
2. A dialog will be shown to you. Press the `I accept the risk` button.
3. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
4. Go to your Firefox profile:`$HOME/.mozilla/firefox/XXXXXXX.default-release/`
5. Create a folder and name it **`chrome`** (with lowercase) and then paste the `userChrome.css` and `userContent.css` (There should be only one `userContent.css` ) files into it.
6. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/)
7. E N J O Y 🦊

### Linux considerations

Firefox uses the GTK3 theme you have to design the menus and the colors. The theme in the screenshots will not look like yours. It can also be useful if you don't want to change a lot of code in the URL-Bar or menus.