# KWidget Sample
This is an example project of using KWidget on an android application.

## What is KWidget?
Easy use form widget components with material design which contains from KEditText and KSpinner

<img width="400dp" src="https://github.com/kredibel-id/SampleKWidget/blob/main/ezgif-2-204eb5c2f1.gif?raw=true"/>

## Getting started
### Support API Level
![minsdk](https://img.shields.io/badge/Min%20SDK-API%2021-%233DDC84?logo=android) ![targetsdk](https://img.shields.io/badge/Max%20Support-API%2031-%233DDC84?logo=android)


## Setup
#### 1. Add kredibel repository.
```groovy
maven{url 'https://repo.repsy.io/mvn/kredibel/sdk'}
```
You can do this in two alternative ways.
- Latest way(Gradle 7+) : Add repository in dependencyResolutionManagement in setting.gradle.
```groovy
dependencyResolutionManagement {
    repositories {
        ...
        ...
        maven{url 'https://repo.repsy.io/mvn/kredibel/sdk'} // <—-- add this
    }
}
```
- Old way : Add repository in build.gradle file at Project level.
```groovy
allprojects {
    repositories {
       ...
       ...
       maven{url 'https://repo.repsy.io/mvn/kredibel/sdk'} // <—-- add this 
    }
}
```

#### 2. Add this dependency to gradle script on app module.
```groovy
dependencies {
    implementation 'io.kredibel:widget:0.0.1' // Please check latest version
}
```

## How to Use
```xml
<io.kredibel.widget.KEditText
      android:hint="Ketik Nama disinih.."
      android:layout_width="200dp"
      android:layout_height="wrap_content"/>
```
      
```xml
<io.kredibel.widget.KSpinner
      android:layout_width="200dp"
      android:layout_height="wrap_content"
      android:entries="@array/platform"/>
```      

## Custom Color Hint
You can customize color by adding the following key to your color resource xml.
```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
  ...
  ...
  <color name="common_color_focused">#0169FF</color>
  <color name="common_color_bg">#F3F5F8</color>
</resources>
```