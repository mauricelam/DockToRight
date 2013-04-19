DockToRight
===========

Chrome dev tools theme designed for use with dock-to-right feature. It optimizes the panels so that it is usable being tall and slim. 

## Features
- New dock icons (mostly to make them occupy less space)
- Vertical split view instead of horizontal
- Scrollable Network tab
- Console as first tab (so it's visible even if you don't have space for all tabs)
- Sliding Styles panels by pressing Esc (when you are focusing on the styles instead of the DOM tree)

## Compatibility
Currently this theme is designed for the Mac. I think it would work on Windows and Linux but I didn't test those. I suspect there will be some minor issues, and I will be glad if anyone is willing to fix those. 

I have tested this on the current Chrome Canary (v28) and Chrome Stable (v26), as of 18th Apr, 2013. Let me know if there are any issues with these or other versions. 

## Chromium Issue

There is a related Chromium issue that will get Chromium developers' attentions and efforts on the issue. Star this issue to see the changes built into Chrome as soon as possible. 

Feb 18 2013: I believe work has already started. Starting to see general class names for split view panels. Yay!

## Installation

Copy `Custom.css` to `User Stylesheets` in your Chrome profile directory. 
The exact location of the profile path can be found in chrome://version. 

The default locations of the folders are as listed: 

Mac: `~/Library/Application Support/Google/Chrome/Default/User StyleSheets/Custom.css`

PC: `C:\Users\YourUsername\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\Custom.css`

Ubuntu (Chromium): `~/.config/chromium/Default/User StyleSheets/Custom.css`

Credits to [Darcy Clarke](http://darcyclarke.me/) and his sources for the file locations

For more details on how to install the theme, see [this blog post](http://darcyclarke.me/design/skin-your-chrome-inspector/)

## Screenshots

Elements tab
![Elements tab](http://mauricelam.github.com/DockToRight/images/elements.png)

Network tab
![Network tab](http://mauricelam.github.com/DockToRight/images/network.png)

## Customization

I have divided the CSS script into sections. Sections are separated by an exaggerated 3-line block comment, with a title in it describing the contents below. Each section can stand on its own, so you can delete the ones you don't need. 
Additional one-line comments is available for more details. In general, blocks separated by one-line comments should be used with the whole section, except for `(optional add-on)`, which if you use the section, you can separately decide whether to include the add-on. 

## Known Issues

- The bottom bar does not work well (parts of it is still not visible / clickable)
