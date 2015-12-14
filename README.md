# electron-app-sample
http://electron.atom.io/

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
iconutil -c icns sample.iconset
```

### Build app

```
electron-packager . sampleApp --platform=darwin --arch=x64 --version=0.36.0 --icon=sample.icns
```