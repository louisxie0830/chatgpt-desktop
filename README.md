# ChatGPT Desktop

> Unofficial ChatGPT Desktop app

*OS X 10.8+, Windows 7+ & Linux are supported.*

## Install

### OS X

[**Download**](https://github.com/louisxie0830/chatgpt-desktop/releases), unzip, and move `ChatGPT.app` to the `/Applications` directory.

### Linux

[**Download**](https://github.com/louisxie0830/chatgpt-desktop/releases) and unzip to some location.

To add a shortcut to the app, create a file in `~/.local/share/applications` called `ChatGPT.desktop` with the following contents:

```
[Desktop Entry]
Name=ChatGPT
Exec=/full/path/to/folder/ChatGPT
Terminal=false
Type=Application
Icon=/full/path/to/folder/ChatGPT/resources/app/static/Icon.png
```

### Windows

[**Download**](https://github.com/louisxie0830/chatgpt-desktop/releases) and unzip to some location.


## Dev

Built with [Electron](http://electron.atom.io).

###### Commands

- Init: `$ npm install`
- Run: `$ npm start`
- Build OS X: `$ npm run build:macos`
- Build Linux: `$ npm run build:linux`
- Build Windows: `$ npm run build:windows`
- Build all: `$ brew install --cask wine-stable` and `$ npm run build` *(OS X only)*

## License

MIT © [Nix Xie](https://github.com/louisxie0830)
