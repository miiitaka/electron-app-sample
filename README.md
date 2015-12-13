# electron-app-sample

### Install

```
npm -g install electron-prebuilt
```

### Execute

```
electron .
```

### Build Package install

```
npm i electron-packager -g
```

### Create icon

```
iconutil -c icns seiyaan.iconset
```

### Build app

```
electron-packager . seiyaan --platform=darwin --arch=x64 --version=0.30.0 --icon=seiyaan.icns
```