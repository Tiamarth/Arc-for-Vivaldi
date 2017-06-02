# Arc-for-Vivaldi  

Arc for Vivaldi is a custom css file that integrates Vivaldi's UI with [Arc,](https://github.com/horst3180/Arc-theme) a popular theme for Linux.

## Features:

- When the current theme is set to apply accent color to window, remove Vivaldi's header gradient.
- Use custom fonts in Vivaldi's interface, by default AFV uses Roboto/
- Dynamic 1px border around Vivaldi that persists even when Native Window is disabled in the settings.
- Hide Vivaldi's built-in titlebar when GUI is hidden.
- Use Arc's window buttons even when Native Window is disabled in the settings.
- Make tab stack indicators Arc-blue, like running application indicators.
- Scrollbars are more minimal.
- Use Arc's sidebar color even on light themes, unless using the opera panel addon.
- Use Arc's toolbar color for start page navigation.
- Optionally make the panel appear to merge with the Vivaldi menu icon, similar to Opera's panel.

## Installation

### Linux

1. Find `style` in your Vivaldi install directory. That should be something like `/opt/vivaldi-snapshot/resources/vivaldi/style`  
2. Save `arc.css` in the style folder. (You should be left with a path such as `resources/vivaldi/style/arc.css`)  
3. If you want to use the opera panel addon, save `opera-panel.css` in style.  
4. If you want to use the Arc window buttons instead of Vivaldi's default window buttons, save the `arc` folder in style as well.  
5. Open `resources/vivaldi/browser.html` in a text editor. Add the following to `<head>`: <link rel="stylesheet" href="style/arc.css" />`  
   If you want to use the opera panel addon, also add `<link rel="stylesheet" href="style/opera-panel.css" />`

### Windows

1. Find `style` in your Vivaldi install directory. That should be something like `C:\Users\[username]\AppData\Local\Vivaldi\Application\[version]\resources\vivaldi\style`  
2. Save `arc.css` in the style folder. (You should be left with a path such as `resources\vivaldi\style\arc.css`)  
3. If you want to use the opera panel addon, save `opera-panel.css` in style.  
4. If you want to use the Arc window buttons instead of Vivaldi's default window buttons, save the `arc` folder in style as well.  
5. Open `resources\vivaldi\browser.html` in a text editor. Add the following to `<head>`: `<link rel="stylesheet" href="style/arc.css" />`  
   If you want to use the opera panel addon, also add `<link rel="stylesheet" href="style/opera-panel.css" />`

### Mac

1. Find `style` in your Vivaldi install directory. That should be something like `/Applications/Vivaldi.app/Contents/Versions/[version]/Vivaldi Framework.framework/Resources/vivaldi/style`  
2. Save `arc.css` in the style folder. (You should be left with a path such as `Resources/vivaldi/style/arc.css`)  
3. If you want to use the opera panel addon, save `opera-panel.css` in style.  
4. If you want to use the Arc window buttons instead of Vivaldi's default window buttons, save the `arc` folder in style as well.  
5. Open `Resources/vivaldi/browser.html` in a text editor. Add the following to `<head>`: `<link rel="stylesheet" href="style/arc.css" />`  
   If you want to use the opera panel addon, also add `<link rel="stylesheet" href="style/opera-panel.css" />`

**Note:** *You may like the way this theme generally looks but not want to use Arc's window buttons. If you'd prefer not to use Arc's window buttons, open `arc.css` in a text editor and find line 135 for instructions on how to not use them.*

**Also note:** *Because Vivaldi features a built-in theme editor, it is easier to create a custom Arc theme and then to use this CSS on top of that theme. This custom CSS is necessary to integrate with Arc because you cannot currently customize every aspect of Vivaldi from the editor.*

### Arc theme settings:

Background: #e7e8eb  
Foreground: #7a8b94  
Highlight: #5294e2  
Accent: #f9f9fa  
✔ Transparent Tabs  
Corner Rounding: 2px

### Arc Dark theme settings:

Background: #2f343f  
Foreground: #d3dae3  
Highlight: #5294e2  
Accent: #383c4a  
✔ Transparent Tabs  
Corner Rounding: 2px
 
### Arc Darker theme settings:

Background: #f5f6f7  
Foreground: #7a8b94  
Highlight: #5294e2  
Accent: #2f343f  
✔ Apply Accent Color to Window  
✔ Transparent Tabs  
Corner Rounding: 2px

## Screenshots:

### Themes with AFV css installed:

[Arc](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc.png)

[Arc Dark](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-dark.png)

[Arc Darker](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-darker.png)

### Themes without AFV installed:

[Vivaldi default](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/default.png)

[Arc](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-nocss.png)

[Arc Dark](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-dark-nocss.png)

[Arc Darker](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-darker-nocss.png)

### Side by side comparisons of themes with and without AFV installed:

[Arc](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-compare.png)

[Arc Dark](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-dark-compare.png)

[Arc Darker](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-darker-compare.png)

[AFV thread on the Vivaldi forums](https://forum.vivaldi.net/post/137297)  
[pre-github changelog](https://github.com/Tiamarth/Arc-for-Vivaldi/blob/master/changelog.txt)
