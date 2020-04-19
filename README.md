# sass-crash-tut

### using compiling sass to css using sass module
- Have node.js installed
- sass (run: `npm i -g sass` to install sass global)
- In the project directory run: `sass --watch scss/style.scss css/style.css`.

### using vscode extension Live Sass Compiler
- https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass
- VSCode settings.json:
```
    "liveServer.settings.donotShowInfoMsg": true,
    "liveSassCompile.settings.formats": [
        {
            "format": "compressed",
            "extensionName": ".css",
            "savePath": "/css"
        }
    ],
    "liveSassCompile.settings.generateMap": false,
```
