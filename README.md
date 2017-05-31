# Arc-for-Vivaldi
[changelog](https://github.com/Tiamarth/Arc-for-Vivaldi/blob/master/changelog.txt) | last updated: 05/31/17 | current version: 3.1
----

Arc for Vivaldi is a custom css file that integrates Vivaldi's UI with [Arc,](https://github.com/horst3180/Arc-theme) a wildly popular theme for Linux.

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

## Installation:

Because Vivaldi features a built-in theme editor, it is easier to create a custom Arc theme and then to use this CSS on top of that theme. This custom CSS is necessary to integrate with Arc because you cannot currently customize every aspect of Vivaldi from the editor.

### Arc theme settings:

Background: #f9f9fa  
Foreground: #5c616c  
Highlight: #5294e2  
Accent: #e7e8eb  
✔ Apply Accent Color to Window  
✔ Transparent Tabs  
Corner Rounding: 2px

### Arc Dark theme settings:

Background: #2f343f  
Foreground: #d3dae3  
Highlight: #5294e2  
Accent: #424959  
✔ Transparent Tabs  
Corner Rounding: 2px
 
### Arc Darker theme settings:

Background: #f5f6f7  
Foreground: #5c616c  
Highlight: #5294e2  
Accent: #2f343f  
✔ Apply Accent Color to Window  
Corner Rounding: 2px
 
### The rest:

1. Put `arc.css` in `/resources/vivaldi/style`
2. To use the opera panel addon, put `opera-panel.css` in `/resources/vivaldi/style`
3. To use Arc's window controls without Native Window enabled, put `/arc` in `/resources/vivaldi/style`  
    Alternatively, if you prefer, you could ignore this step and continue using Vivaldi's default window buttons. AFV removes their background, which makes them more minimal.
4. Open `/resources/vivaldi/browser.html`
5. In the `<head>`, paste the following:
    <link rel="stylesheet" href="style/arc.css" />
    <link rel="stylesheet" href="style/opera-panel.css" />
6. The scrollbars will only affect Vivaldi's UI and, as far as I know, there's nothing I can do about this. But I wrote a user style that will affect web pages as well, and you can install it [here.](https://userstyles.org/styles/142645/arc-scrollbars)
7. Relaunch Vivaldi.

[AFV thread on the Vivaldi forums](https://forum.vivaldi.net/post/137297)

## Screenshots:

### Themes with AFV css installed:

Arc  
![Arc](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc.png)

Arc Dark  
![Arc Dark](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-dark.png)

Arc Darker  
![Arc Darker](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-darker.png)

### Themes without AFV installed:

Default  
![Vivaldi default](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/default.png)

Arc  
![Arc](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-nocss.png)

Arc Dark  
![Arc Dark](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-dark-nocss.png)

Arc Darker  
![Arc Darker](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-darker-nocss.png)

### Side by side comparisons of themes with and without AFV installed:

Arc  
![Arc](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-compare.png)

Arc Dark  
![Arc Dark](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-dark-compare.png)

Arc Darker  
![Arc Darker](https://raw.githubusercontent.com/Tiamarth/Arc-for-Vivaldi/master/scrots/arc-darker-compare.png)
