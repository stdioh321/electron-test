# Electron Test - Mundijuegos with Flash

# Instalation
```sh
$ cd electron-test
$ npm install
$ npm install -D -g electron-packager
```

# Run
```sh
$ npm start
```


# Build as a native application
Run the commands inside the source folder
```sh
$ cd electron-test
```
# # Windows
```sh
$ electron-packager . [APPLICATION-NAME] --platform=win32 --arch=x64 --overwrite
```
Exemple:
```sh
$ electron-packager . mysuperapp --platform=win32 --arch=x64 --overwrite
```

# # MacOS

```sh
$ electron-packager .  [APPLICATION-NAME] --platform=darwin --overwrite
```