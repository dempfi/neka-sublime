# Neka Theme for Sublime Text 3
Dark and bright theme for Sublime Text 3.

***

## Screenshot

![Screenshot](/neka.png)
The font used in the screenshot is [__Roboto Mono__](https://www.google.com/fonts/specimen/Roboto+Mono).

***

### How to Install
#### Via Package Control

The easiest way to install is using [Package Control](https://packagecontrol.io/), where Neka is listed as `Neka Theme`.

1. Open Command Palette using menu item `Tools -> Command Palette...`
2. Choose `Package Control: Install Package`
3. Find `Neka Theme` and hit <kbd>Enter</kbd>
4. Activate the theme by prefs below at *Preferences > Setting - User*:
```json
"theme": "Neka.sublime-theme",
"color_scheme": "Packages/Neka Theme/Neka.tmTheme",
```

#### Manual

You can also install the theme manually:

1. [Download the latest release .zip](https://github.com/dempfi/Neka-Theme/releases), extract to folder *"Neka Theme"*.
2. Move "Neka Theme" folder inside the Packages directory. *Preferences > Browse packages...*
3. Activate the theme by prefs below at *Preferences > Setting - User*:
```json
"theme": "Neka.sublime-theme",
"color_scheme": "Packages/Neka Theme/Neka.tmTheme",
```
4. Restart Sublime and enjoy!

***

### Settings

For norrow statusbar use
```json
"neka_theme_small_statusbar": "true"
```

If you need some options just open issue and I'll add some settings.

### Thanks
Thanks to [Mattia Astorino](https://github.com/equinusocio) for the inspiration and really good Material Theme.
