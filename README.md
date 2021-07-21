# Electron Auto-Update POC

### Run it

```bash
npm install
npm start
```

### Create a draft release with a built artifact

```bash
npm run deploy
```

### Supported packaging methods

* macOS (Squirrel.Mac)
* Windows (NSIS)
* Linux (AppImage)

You'll have to use `autoUpdater` object from `electron` if you are using Squirrel.Mac and Squirrel.Windows, [which neither doesn't support Linux](https://www.electronjs.org/docs/api/auto-updater).  
This repository is just for demonstration and configured to build `deb` package, which doesn't work for `electron-updater`.  
