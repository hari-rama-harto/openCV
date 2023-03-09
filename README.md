OPENCV LIBRARY FOR ANDROID NATIVE MODULE

HOW TO USE:

1. Add maven jitpack on repositories block at project root (android) build.gradle, such as:
allprojects {
    repositories {
        maven { 
            name "jitpack"
            url "https://jitpack.io" 
        }
    }
}

2. Add implementation on dependencies block at project app (android/app) build.gradle, such as:
dependencies {
    implementation 'com.github.hari-rama-harto:openCV:+'
}


REFFERENCES:

Quick Start
https://opencv.org/android/

Release
https://opencv.org/releases/
