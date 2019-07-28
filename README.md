# FFmpeg Android build script

这是一个编译 Android app可以使用的FFmpeg库的脚本

This is a shell script to build FFmpeg libraries for Android apps.

Tested with:

* FFmpeg 4.1
* android-ndk-r17c

## 使用 Usage

* 编译多平台
* To build everything:

        ./build-ffmpeg.sh

* 编译 armv8-a
* To build armv8-a libraries:

        ./build-ffmpeg.sh armv8-a

* 编译 armv7-a x86_64
* To build fat libraries for armv7-a and x86_64 (64-bit simulator):

        ./build-ffmpeg.sh armv7-a x86_64

## Download

You can download a binary for FFmpeg 4.1 release at https://downloads.sourceforge.net/project/ffmpeg-ios/ffmpeg-ios-master.tar.bz2
