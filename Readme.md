# Apache Cordova based ManageGuru frontend

Manageguru is a business analytics website. This is it's Apache Cordova mobile frontend.

Built in Electron packaged with Electron Forge

## How to run

1. Install [Node.js and NPM](https://nodejs.org/en/)
3. Install Electron Forge with `npm install -g cordova`
3. Setup [Android SDK and Build tools or platform specific tools here](https://cordova.apache.org/docs/en/latest/guide/cli/index.html)
4. Add platforms with `cordova add platform android` and `cordova add plaform browser` and so on
5. If you want to run as a web server, use `cordova run browser`, else build for another platform
6. If you want to build for a platform, build with `cordova build android` for android (replace android with your plaform) or `cordova build` for all your platforms which should produce a package for your plaform such as an `apk`
