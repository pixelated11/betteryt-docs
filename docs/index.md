# Better Youtube
***
A multiplatform desktop Youtube client made using electron, that features a built-in adblocker, and some usercript.

## What is Better Youtube?
***
BetterYT is a desktop Youtube client that is built on electron. It features an electron-adblocker, and some youtube userscripts. It currently supports multiple platforms, such as Windows, and Linux. Don't worry about the RAM usage. This app has optimized electron, so that it uses less RAM than usual, without losing performance.

## How to install
***
Head over to the github repository's releases page [here](https://github.com/pixelated11/better-youtube/releases) then, download the installer/portable app, according to your operating system. If you don't want to download the ready-binary, you can build it your own using the guide below.

## Building the app
***
To build the app, you must first install the dependencies needed:
- Node.js v18.0+
- npm v8+
- Git

To start, clone the repo (or download the ZIP file and extract it) , and navigate yourself to the repository folder:
```
git clone https://github.com/pixelated11/better-youtube

cd better-youtube
``` 
Then, install the required npm dependencies:
```
npm install
```
After that, build the app:
### For Linux
To build .deb and .appimage file for linux, run:
```
npm run build:linux
```
The executable should be in the `dists/` folder.
### For Windows
To build the application for windows, run:
```
npm run build:windows
```
The portable app and the installer should be in `dists/` folder.

## Running it directly
Simply run this command in the repository directory to run it directly:
```
npm run start
```

## Contributing to this project
If you would like to contribute to this project, feel free to do so. Contact me with this e-mail: itspixelatd@proton.me
Consider starring the repo!