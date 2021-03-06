![](https://github.com/alamshafil/HaxPro/blob/master/logos/logo-full.png)


[![](https://api.travis-ci.com/alamshafil/HaxPro.svg?branch=master)](https://travis-ci.com/alamshafil/HaxPro)
[![](https://david-dm.org/alamshafil/HaxPro.svg)](https://david-dm.org/alamshafil/HaxPro)
[![](https://snyk.io/test/github/alamshafil/HaxPro/badge.svg)](https://snyk.io/test/github/alamshafil/HaxPro)
[![](https://img.shields.io/twitter/follow/FuriousDevYT?style=social)](https://www.twitter.com/FuriousDevYT)

A scripting language designed to be robust and easy.

# Build Instructions
To get started, download the latest source code from Github.

To build [HaxPro](https://github.com/alamshafil/HaxPro/) you need to install the following:
* [`node.js`](https://nodejs.org/)
* [`electron-packager`](https://github.com/electron/electron-packager)

First install [`node.js`](https://nodejs.org/), you will install [`electron-packager`](https://github.com/electron/electron-packager) later.

Once you have installed [`node.js`](https://nodejs.org/) open your terminal and go to where have downloaded the source code.

For example, I downloaded the source to `C:\Users\Admin\Desktop\HxPro` 

I would type the following in the terminal:
```
cd C:\Users\Admin\Desktop\simple
```

Once you have performed the command, type:
```
npm install electron-packager -g
```

This will install [`electron-packager`](https://github.com/electron/electron-packager) onto your machine.

After it is completed installing, you can type `electron-packager` to build executables.

You can read the documentation on using `electron-packager` [here](https://github.com/electron/electron-packager).

The following is basic usage of `electron-packager` in the command line:
```
electron-packager <sourcedir> <appname> --platform=<platform> --arch=<arch> [optional flags...]
```

For example I want to compile a 64-bit `.exe` for Windows, I would type:

```
electron-packager . HaxPro —-platform=win32 —-arch=x64
```
