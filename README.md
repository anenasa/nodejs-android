# nodejs-android
Unofficial minimal nodejs build for android

This build is for use with yt-dlp as external JS runtime, based on Termux build script with some modifications:
1. Build without amaro, inspector, intl, and sqlite to save space.
2. Static link to libc++_shared, c-ares, openssl, and zlib so the node binary is self-contained.

Build script is available [here](https://github.com/anenasa/termux-packages/tree/nodejs).
