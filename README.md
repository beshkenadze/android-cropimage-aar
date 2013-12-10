android-cropimage
========================

android-cropimage library built with gradle in aar format for usage with android gradle build system. 

How to use
=======================
Before you can get aar you should checkout [https://github.com/lvillani/android-cropimage](https://github.com/lvillani/android-cropimage) submodule. Overall build process including build is straightforward:
```bash
  $ git submodule update --init
  ...
  $ ./gradlew build
  ...
```

When build is finished aar file will be located in `build/libs`.

Maven artifact in local repo
======================

```bash
  $ ./gradlew build uploadArchives
```
