<div align="center">
<h1>SimplerentFox: 🦊 Windows Version</h1>
</div>

![](https://github.com/MiguelRAvila/SimplerentFox/blob/master/Images/win.png)

### Installation

1. In the searchbar type `about:config`
2. A dialog will be shown to you. Press the `I accept the risk` button.
3. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
4. Go to your Firefox profile:`C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
5. Create a folder and name it **`chrome`** (with lowercase) and then paste the `userChrome.css` and `userContent.css` (There should be only one `userContent.css` ) files into it.
6. In addition to the `userChrome.css` and `userContent.css` files you'll also need the `dark_additional_windows.css`, `dark_checkboxes_and_radios.css` and `dark_context_menus.css` files in your **chrome** directory
7. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/)
8. E N J O Y 🦊

> ### Transparency Note
>
> Transparency in Windows breakes the window behavior. You can change the colors in the variable section of the code and still add transparency, but the window manager will have some bugs with maximized firefox.