# Opencv-Android-3.3-gradle
## Introduction
This repository is created to avoid the gradle problems with the OpenCV java sdk, usually if you are going to use OpenCV CameraBridge.

## How to add the gradle dependency?
### 1.- Add this code in your root gradle file (build.gradle):
```javascript
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```
### 2.- Add the compile line in your app/build.gradle.
```javascript
compile 'com.github.uelordi01:Opencv-Android-3.3-gradle:1.1'
```
And that's it.
