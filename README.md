# Afterglow

![Afterglow magenta](Screenshots/Afterglow-magenta.png)

Afterglow is a minimal dark Theme for Sublime Text 2 and 3. Also it is a syntax color scheme. The theme is based on the great theme [Spacegray](https://github.com/kkga/spacegray). The syntax color scheme is mostly derived from [idlefingers](http://idlefingers.co.uk/).

**Special thanks** to Max Riveiro [@kavu](https://github.com/kavu) for add a lot of icons for sidebar to this repository.

This repository is [a fork of YabataDesign/afterglow-theme](https://github.com/YabataDesign/afterglow-theme) with a few modifications. It isn't necessarily in sync or up-to-date with the original. If you're just getting started with Afterglow, I recommend you go there first!

### Installation and activation

The easiest way to install _the official/original version_ is by using [Sublime Package Control](https://sublime.wbond.net/).

* Open `Command Palette` using menu item `Tools -> Command Palette...`, or `Cmd+Shift+P` (OS X) `Ctrl+Shift+P` (Win/Linux)
* Type `Package Control: Install Package`
* Search `Theme - Afterglow`

Of course, this fork exists because we don't want the original, so, follow these steps instead:

* Locate your Sublime Text `Packages directory` by using the menu item `Preferences -> Browse Packages...`.
* Then, clone the repository using this command: `git clone https://github.com/barryhughes/afterglow-theme/ "Theme - Afterglow"`

Activate this theme and color scheme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User`.

Then add the following code settings, depending on the theme you choose. **(After activating the theme, you must restart Sublime Text.)**

### Settings for Afterglow

```json
{
    "theme": "Afterglow.sublime-theme",
    "color_scheme": "Packages/Theme - Afterglow/Afterglow.tmTheme",
    /* ...other settings as desired... */
}
```

To switch between different colours/hues, change `"Afterglow.sublime-theme"` (as per the above example) to one of the following:

* Blue `"Afterglow-blue.sublime-theme"`
* Magenta `"Afterglow-magenta.sublime-theme"`
* Orange `"Afterglow-orange.sublime-theme"`
* Green `"Afterglow-green.sublime-theme"`

Icon configuration:

* Remove icons with `"sidebar_no_icon": true`
* Hide folder icons `""folder_no_icon": true`

Setting the tab height (pretty damn large by default):

* Medium size `"tabs_medium": true`
* Smaller `"tabs_small": true`

## Color schemes

### Afterglow - Monokai

![Afterglow Monokai](Screenshots/Afterglow-monokai.png)

Besides color scheme by default, you can use the color scheme `Afterglow - Monokai` based on the original `Monokai`, slightly modified to be consistent with the Theme colors.

You must add this in your user preferences file `Sublime Text -> Preferences -> Settings - User`:

```json
{
    "color_scheme": "Packages/Theme - Afterglow/Afterglow-monokai.tmTheme"
}
```


### Afterglow - Twilight

![Afterglow Twilight](Screenshots/Afterglow-twilight.png)

If you prefer, you can use the color scheme `Afterglow - Twilight` (very slightly modified from the original), adding this to the user preferences file `Sublime Text -> Preferences -> Settings - User`:

```json
{
    "color_scheme": "Packages/Theme - Afterglow/Afterglow-twilight.tmTheme"
}
```


### Markdown

![Afterglow markdown](Screenshots/Afterglow-markdown.png)

**NEW:** This color scheme support **Github Flavored Markdown**.

#### To enable Afteglow for Markdown

(I highly recommend installing [Sublime Markdown Extending plugin](https://github.com/jonschlinkert/sublime-markdown-extended).)

First, **open a markdown(.md) file**, then navigate to `Sublime Text -> Preferences -> Settings - More -> Syntax Specific - User` in the menu bar.

Add to your current settings or replace with the following:

```json
{
    "color_scheme": "Packages/Theme - Afterglow/Afterglow-markdown.tmTheme",
    "draw_centered": false,
    "draw_indent_guides": false,
    "trim_trailing_white_space_on_save": false,
    "word_wrap": false,
    "wrap_width": 130
}
```
