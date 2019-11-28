# buildCreation
android and ios build creation

# Evironment variable setup : MAC
below code required in .bash_profile file, which is available in user folder. Java and android sdk need to placed as per the folder structure which mentioned in the below code.  once updated the below information in the file then user "source ~/.bash_profile" to set the changes in the mac.

export JAVA_HOME=$(/usr/libexec/java_home)

export ANDROID_HOME=/Users/jose/android-sdk-macosx

export PATH=$PATH:$ANDROID_HOME/build-tools
export PATH=$PATH:$ANDROID_HOME/build-tools/29.0.2

export PATH=$PATH:$ANDROID_HOME/emulator

export PATH=$PATH:$ANDROID_HOME/platform-tools

export PATH=$PATH:$ANDROID_HOME/platforms
export PATH=$PATH:$ANDROID_HOME/platforms/android-29

export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/tools/lib


export ANDROID_SDK_ROOT=/Users/jose/android-sdk-macosx

export PATH=$PATH:$ANDROID_SDK_ROOT/build-tools
export PATH=$PATH:$ANDROID_SDK_ROOT/build-tools/29.0.2

export PATH=$PATH:$ANDROID_SDK_ROOT/emulator

export PATH=$PATH:$ANDROID_SDK_ROOT/platform-tools

export PATH=$PATH:$ANDROID_SDK_ROOT/platforms
export PATH=$PATH:$ANDROID_SDK_ROOT/platforms/android-29

export PATH=$PATH:$ANDROID_SDK_ROOT/tools
export PATH=$PATH:$ANDROID_SDK_ROOT/tools/bin
export PATH=$PATH:$ANDROID_SDK_ROOT/tools/lib


export GRADLE_HOME=/Users/jose/gradle/gradle-5.6.3
export PATH=$PATH:$GRADLE_HOME/bin

# Setting PATH for Python 3.8
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.8/bin:${PATH}"
export PATH

#source ~/.bash_profile
if [ -f ~/.git-completion.bash ]; then
  . ~/.git-completion.bash
fi

Referal links
https://ionicframework.com/docs/v3/developer-resources/platform-setup/mac-setup.html
https://ionicframework.com/docs/installation/android





# how to set up the emulator using android studio
https://medium.com/@dalenguyen/working-with-android-emulator-through-command-line-b3a96965566f
https://developer.android.com/studio/command-line/sdkmanager
https://stackoverflow.com/questions/35476182/updating-google-play-services-in-emulator
https://ionicframework.com/docs/cli/commands/cordova-emulate

https://www.venafi.com/education-center/code-signing/what-is-code-signing#benefitofcodesigning
