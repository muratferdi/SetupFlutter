# SETUP FLUTTER WITH COMMAND LINE - WITHOUT ADNROID STUDIO 2023 WORKING SOLUTION


ANDROID_HOME > D:\AndroidSDK

ADNROID_SDK_ROOT > D:\AndroidSDK

JAVA_HOME > C:\Program Files\Java\jdk-17\


Add Path; 

D:\AndroidSDK\cmdline-tools\latest\bin

D:\AndroidSDK\emulator

D:\AndroidSDK\platform-tools

D:\flutter\bin

C:\Program Files\Java\jdk-17\bin



sdkmanager --update

sdkmanager "platforms;android-33"

sdkmanager "build-tools;33.0.2"

sdkmanager --install "cmdline-tools;latest"

sdkmanager "system-images;android-30;google_apis;x86"

avdmanager create avd --force --name "TEST" --device "pixel" --package "system-images;android-30;google_apis;x86"

