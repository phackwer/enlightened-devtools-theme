# enlightened Theme
A not so minimal theme for the Chrome Developer Tools.
Modifies Elements and Console view, other views are on the way.
Forked from https://github.com/frontdevDE/mnml-devtools-theme

Tested on Mac.

## Installation 
Just locate the `User Stylesheets` directory and override the `Custom.css`:

**Mac:** `~/Library/Application Support/Google/Chrome/Default/User StyleSheets/Custom.css`

**PC:** `C:\Users\YourUsername\AppData\Local\Google\Chrome\UserData\Default\User StyleSheets\Custom.css`

**Ubuntu (Chromium):** `~/.config/chromium/Default/User StyleSheets/Custom.css`

## Customization
Feel free to fork and customize the theme to your needs. Missing some selectors? Just navigate Chrome to `chrome-devtools://devtools/devTools.css` and get a detailed list of nearly all possible selectors and their default styles.

To inspect the dev tools inspector, undock the inpector, then press cmd+alt+i.

## Compiling Less to CSS
You will need to have the less compiler installed. If it's not installed already, you can install it via npm:

`[sudo] npm install -g less`

Compile Less to CSS:
`lessc Custom.less Custom.css`

Now copy the freshly compiled css to your Chrome installation:
`cp Custom.css ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets`

## Screenshots
![Screenshot](https://raw.github.com/vincentmac/enlightened-devtools-theme/master/resources/screenshot.png)
![Screenshot1](https://raw.github.com/vincentmac/enlightened-devtools-theme/master/resources/screenshot1.png)