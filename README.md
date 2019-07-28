# FFmpeg Android build script

����һ������ Android app����ʹ�õ�FFmpeg��Ľű�

This is a shell script to build FFmpeg libraries for Android apps.

Tested with:

* FFmpeg 4.1
* android-ndk-r17c

## ʹ�� Usage

* �����ƽ̨
* To build everything:

        ./build-ffmpeg.sh

* ���� armv8-a
* To build armv8-a libraries:

        ./build-ffmpeg.sh armv8-a

* ���� armv7-a x86_64
* To build fat libraries for armv7-a and x86_64 (64-bit simulator):

        ./build-ffmpeg.sh armv7-a x86_64

## Download

You can download a binary for FFmpeg 4.1 release at https://downloads.sourceforge.net/project/ffmpeg-ios/ffmpeg-ios-master.tar.bz2
