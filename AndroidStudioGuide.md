## Android Studio Guide

### Objectives
Document common tasks in Android Studio, starting from version 0.8.6.

### Tasks

#### Change project api level, target SDK
Right click on the module, select "Open Module Settings". The project Structure window will open. In the Flavors tab you will find how to customize the minimum and target SDK. This changes the file build.gradle. The AndroidManifest.xml does not need to have minSdkVersion or TargetSdKVersion, as this is overridden by Gradle.

![Configure target SDK](/images/img0001.jpg)
