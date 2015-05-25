# Homey Development Kit

Create Homey apps with ease! If you're only looking to get the Development Kit, download a pre-built version from [https://developers.athom.nl]().

This repository is meant for development of the Development Kit itself.

![](https://developers.athom.nl/img/devkit.png)

### Run instructions

1. clone this repo ```git clone https://github.com/athombv/devkit.git```
2. cd to the directory ```cd devkit```
3. install the submodule ```git submodule update --init --recursive``` for the devkit-core
4. install the node packages ```npm install```
5. install the bower packages ```./node_modules/.bin/bower install```
6. run the grunt builder ```./node_modules/.bin/grunt  ``` to compile the depencencies
7. Download a pre-built nw.js binary from http://nwjs.io, and execute `nw .` if you're on OS X or Linux. On Windows, drag the devkit folder on the `nw.exe` binary.

### Docs
Please read them at [devkit-core](https://github.com/printhom/devkit-core).
