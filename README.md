# FirefoxCSS-Safari-theme
A Safari 15 like theme for Firefox 100+ macOS

<p align="center">
  <img src="https://github.com/Pepitortue/FirefoxCSS-Safari-theme/blob/master/Showcase%20Dark.png">
</p>
<p align="center">
  <img src="https://github.com/Pepitortue/FirefoxCSS-Safari-theme/blob/master/Showcase%20Light.png">
</p>

Added window control buttons

<p align="center">
  <img src="https://github.com/xusader/FirefoxCSS-Safari-theme/blob/master/screenshot.png">
</p>


## What is it
This is a Firefox theme for MacOS inspired by Safari. This theme is not meant to reproduce perfectly Safari.
This code contains a mix of code shared by people from r/FirefoxCSS and modifications I made.

## Installation
1. Enable the legacy Firefox CSS customizations by setting the `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` in about:config
2. Copy the userChrome.css file into your Firefox profile directory.
To access this folder, go to about:profiles and click the "Open in Finder" button in front of the first "root directory" line. In the opened Finder window, open the "chrome" folder.
Restart Firefox.
3. Follow the same process with the userContent.css file
4. Restart Firefox

*Note : ShadowFox users only have to copy/paste the code at the end of their userChome.css and userContent.css files.*

### Additional
To enable the blur filter on the pop up URL menu, you need to set the `layout.css.backdrop-filter.enabled` to `true` in about:config
Enable web renderer (at least for MacOS users and Firefox 72) changing the `gfx.webrender.all` to `true` in about:config

## TODO
* Ensure the theme apply as intended for every users and fresh Firefox install

## Issues
This theme was tested with Firefox 100 on macOS Monterey. Graphical differences might occur on other OS.
I will update the theme for every new Firefox release since this is my daily theme.
