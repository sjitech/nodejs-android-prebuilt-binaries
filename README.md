# nodejs-android-prebuilt-binaries
Prebuilt binaries of NodeJS for android(arm,arm64,x86,x64,mipsel), full or limited(by --without-snapshot --without-inspector --without-intl)

These binaries are prebuilt on Linux docker container, see [Build Nodejs For Android Perfectly](https://github.com/sjitech/build-nodejs-for-android).

Each dir has an `all.7z` which contains full install files:
- `bin`: node npm(just a symbol link)
- `extras`: cctest openssl-cli and some host binaries
- `include`: some C/C++ include files
- `lib`: node_modules
- `share`: manual
