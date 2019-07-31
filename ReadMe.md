#  Hybrid Mobile App

## Prerequisites Software
- Install [Nodejs](https://nodejs.org/en/)
  and check version with below command
  >node -v 
  >npm -v
- Install [ionic](https://ionicframework.com/getting-started#cli) globally

        npm i -g ionic
- Install [Cordova](https://cordova.apache.org/#getstarted) globally

        npm i -g cordova
        npm i -g cordova-res
- Install [Android SDk](https://developer.android.com/studio)

        Android SDK Tools
        Android Platform-tools    
        Andorid emulator (Optional)
 - Install [JDK8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
 - Set Environment Variables in windows
  
    | Name | Value |
    | ------ | ------ |
    | ANDORID_HOME | <Android_SDK_Path> |
    | ANDORID_SDK_PATH | <Android_SDK_Path> |
    | JAVA_HOME | <JDK_Installation_Path> |
    | Path | %ANDROID_HOME%\tools |
    | Path | %ANDROID_HOME%\platform-tools  |
    | Path | %ANDROID_HOME%\emulator  |
    | Path | %JAVA_HOME%\bin |

 ## Create ionic+angular application

        ionic start appName sidemenu -type=angular
        
## Run Ionic Application

        ionic serve
## Add platform as Android

        ionic cordova platform add android
        
## Build platform

        ionic cordova build android
       
 Above command build **android platform** and create **unsigned apk** file in the output directory
