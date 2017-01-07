# Electron+Java Demo

Java Desktop Application with HTML 5 UI based on Electron and Vaadin

## Uses

1. Node JS
2. Electron
3. Gradle
4. JDK 8
5. Jetty HTTP Server
6. Vaadin Framework

## Try it!

__Note:__ These steps now are relevant to Windows only.

1. Download and install `npm` from https://nodejs.org/en/download/
2. Install required `npm` modules:
```
> cd electron-src
> npm install
```
3. Build java application:
```
> gradlew installDist
```
4. Run electron demo script:
```
> electron-app-debug.bat
```
5. Build standalone app
```
> electron-app-package.bat
```
6. Application will be bundled to `electron-src\electron-vaadin-win32-x64`