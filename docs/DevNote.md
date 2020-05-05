# Development Note

## Modify Steps

### About x264
- orginal download url is not working. so we need to update url.

### update FFMPEG version
- change ffmpeg version from 3.3.4 to 3.1.1, for my usage.

### modify CMakeLists.txt for macOS 10.15
- modify CMakeList.txt for frei0r by [issue](https://github.com/dyne/frei0r/issues/64)
- copy [file](frei0r_161_fixed_CMakeLists.txt) into frei0r package.
- 