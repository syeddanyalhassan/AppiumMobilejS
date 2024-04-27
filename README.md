Make sure android home is added

ANDROID_HOME



setx ANDROID_HOME "C:\Users\danyal.hassan\AppData\Local\Android\Sdk\"

setx PATH "%PATH%;%ANDROID_HOME%\platform-tools";
setx PATH "%PATH%;%ANDROID_HOME%\tools;
setx PATH "%PATH%;%ANDROID_HOME%\build-tools;
setx PATH "D:\AndroidStudio\bin;

Make sure vysor is connected

Make sure virtual device is created from Android Studio

If code does not work do add following in command prompt

appium driver install uiAutomator2
