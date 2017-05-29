# Visual Studio Code Config - Spotify UI
After changing from Atom to VS Code, I really missed the UI and UX of my [Spotify theme](https://github.com/joseqmatias/spotify-ui). So I decided to bring the same user experience to VS Code.

## Installation
Installation is fairly easy. Just follow these steps:

1. Copy `settings.json` and add to your current settings file. (Make sure you copy/replace **workbench.colorCustomizations**. Other settings are not mandatory.)
2. Download and install Circular font.
3. Download `vscode-spotify.min.css`
4. Apply styles.

    #####  For Windows users
    1. Go to *C:\Program Files (x86)\Microsoft VS Code\resources\app\out\vs\workbench\electron-browser\bootstrap*
    2. Open `index.html` with Administrator priviledges.

    ##### For macOS users
    1. Right-click on VS Code application
    2. Show Package Contents
    3. Go to *Contents\Resources\app\out\vs\workbench\electron-browser\bootstrap*
    4. Open `index.html`


    After this, add ```<link rel="stylesheet" href="file:///<your_path>/vsc-spotify-ui.min.css">``` to <head> in `index.html`. Don't forget to replace <your_path> with the path where you saved the file.

5. Restart VS Code

> Note: If a message shows saying your VS Code is currupted, click "Never Show Again".

## Suggestions
+ In order to have the best UX possible, [One Dark Vivid](https://marketplace.visualstudio.com/items?itemName=kkozee.theme-one-dark-vivid) theme is recommended.
+ Editor font is Menlo.
