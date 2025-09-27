# How to Install Microsoft Store Apps From Command Line?
There is a way to install Microsoft Store apps via Command Line.

## Prerequisites
Winget 1.8 or later

## Installing the App
Just type this into command prompt:
```
winget install <store app id>
```

Example for Free ISO Creator:
```
winget install 9NDP817X3NH4
```

If you own the app the app is free, the app will be installed successfully.

If you don't own the app and the app is free, it will still be installed successfully (may fail if the app is not available in your market).

If you own the app and the app is paid, it will still be installed successfully.

If you don't own the app and the app is paid, installation will fail with error 0x803F8001.

If you try to install a game, you will get the following error:

```
No package found matching input criteria.
```
