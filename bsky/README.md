![preview of Firmament userscript](https://github.com/haraiva/userstyles/blob/main/bsky/screenshots/all-preview.png)

# Firmament
A customisable theme for [Bluesky Social](https://bsky.app) built upon/based on [@fenny.zone](https://bsky.app/profile/fenny.zone)'s amazing ["Better Bluesky" userstyle](https://userstyles.world/style/11956/better-bluesky).

You can freely customise the colours in the Stylus UserCSS configuration menu, or if you just want to borrow some of my colour schemes you can check out my readymade palettes below.

TO DO:
- add image previews to repo
- publish on userstyles.world

## Features:
🌈 Customisable colours: Background, text, accent.  
🌗 Light/Dark modes: Follows system settings.  
🔡 Customisable fonts: System fonts and active fonts. Default is Inter, which is the default bsky font).  
💭 Customisable header symbol: Accepts Emoji!  

![preview of darkmodes in Firmament userscript](https://github.com/haraiva/userstyles/blob/main/bsky/screenshots/darkmode-preview.png)

## Installation
Install using [Stylus](https://github.com/openstyles/stylus) on Chrome and Firefox, and the [Userscripts app](https://github.com/quoid/userscripts) on Safari (desktop and iOS). 

See line 37 of the code for instructions on using it with Safari, or download the file in the [safari folder](https://github.com/haraiva/userstyles/tree/main/bsky/safari), customise it and chuck it into your Userscripts folder.

## Readymade Palettes
Copy the few respective lines of code for each colour palette to replace lines 26-31 (the bit starting with `//🎨 COLOUR PALETTE: `) in the code.

For Safari: It's a little more annoying and you'd have to tweak the uncommented `:root` with the colour scheme of your choice... Maybe I'll make different versions of the same code for this. We'll see.

### mossy forest
![preview of mossy forest theme](https://github.com/haraiva/userstyles/blob/main/bsky/screenshots/forest-preview.png)

```
//🎨 COLOUR PALETTE: mossy forest
@var color tweak-option-accent "Accent" #5f8e76
@var color tweak-option-bg "Light Mode Background" #e6ded4
@var color tweak-option-text "Light Mode Text Color" #2f2b27
@var color tweak-option-bg-dark "Dark Mode Background" #000f10
@var color tweak-option-text-dark "Dark Mode Text Color" #e9daca
```

### secondhand paperback
![preview of secondhand paperback theme](https://github.com/haraiva/userstyles/blob/main/bsky/screenshots/paperback-preview.png)
```
//🎨 COLOUR PALETTE: secondhand paperback
@var color tweak-option-accent "Accent" #b97f05
@var color tweak-option-bg "Light Mode Background" #e6ddd3
@var color tweak-option-text "Light Mode Text Color" #2d2823
@var color tweak-option-bg-dark "Dark Mode Background" #212124
@var color tweak-option-text-dark "Dark Mode Text Color" #d7cfc0
```

### nice day
![preview of nice day theme](https://github.com/haraiva/userstyles/blob/main/bsky/screenshots/niceday-preview.png)
```
//🎨 COLOUR PALETTE: nice day
@var color tweak-option-accent "Accent" #1092a6
@var color tweak-option-bg "Light Mode Background" #e6dfd3
@var color tweak-option-text "Light Mode Text Color" #0c1e2f
@var color tweak-option-bg-dark "Dark Mode Background" #102a39
@var color tweak-option-text-dark "Dark Mode Text Color" #d7cfc0
```

### tequila sunset
![preview of tequila sunset theme](https://github.com/haraiva/userstyles/blob/main/bsky/screenshots/sunset-preview.png)
```
//🎨 COLOUR PALETTE: tequila sunset
@var color tweak-option-accent "Accent" #d95e53
@var color tweak-option-bg "Light Mode Background" #fdf3e0
@var color tweak-option-text "Light Mode Text Color" #380b43
@var color tweak-option-bg-dark "Dark Mode Background" #1b0820
@var color tweak-option-text-dark "Dark Mode Text Color" #d5bfb4
```

## Credits
- based on ["Better Bluesky" userstyle](https://userstyles.world/style/11956/better-bluesky) by [@fenny.zone](https://bsky.app/profile/fenny.zone)