## Convert a Website into an Electron App on Arch Linux

### What is Nativefier?
[Nativefier](https://github.com/nativefier/nativefier) is an open-source command-line tool that turns any web page URL into a standalone Electron desktop application. It basically wraps the site in an Electron shell, making it behave like a native app.

### Why use Nativefier?
- Quick and simple — no custom Electron code required.
- Works perfectly on Arch Linux (or any platform).
- Lets you customize the app’s icon, title, and window options.
- Great way to turn web tools or dashboards into desktop-like apps.

### Installation Steps (Arch Linux)

1. **Install Node.js and npm**
`sudo pacman -S nodejs npm`

2. **Install Nativefier globally**
`npm install -g nativefier` (run with sudo)

3. **Create your app using a website URL**
`nativefier "https://example.com"`


Replace `"https://example.com"` with the website you want to convert.  
Nativefier will automatically generate a folder with the standalone app executable.

4. **Run your new Electron app, itll be inside the folder, home directory if location isnt specified**
