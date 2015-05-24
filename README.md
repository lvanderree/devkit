# Homey Development Kit

Create Homey apps with ease! If you're only looking to get the Development Kit, download a pre-built version from [https://developers.athom.nl]().

This repository is meant for development of the Development Kit itself.

![](https://developers.athom.nl/img/devkit.png)

### Run instructions

1. clone this repo ```git clone https://github.com/athombv/devkit.git```
2. cd to the directory ```cd devkit```
3. install the node packages ```npm install```
4. install the bower packages ```cd www; bower install; cd ..```
5. make a symbolic link (or copy) [devkit-core](https://github.com/printhom/devkit-core) so there's a folder `core` next to `package.json`, `app.js` etc.
6. Download a pre-built nw.js binary from http://nwjs.io, and execute `nw .` if you're on OS X. On Windows, drag the devkit folder on the `nw.exe` binary.

### Docs
Please read them at [devkit-core](https://github.com/printhom/devkit-core).