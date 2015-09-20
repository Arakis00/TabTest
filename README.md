# TabTest
This is a template for a tabbed application with fragments within Android Studio.

# Notes
I went to make my first new Android application in quite some time and found out that the plugin for Eclipse is no longer officially supported, so I'm moving to what is now officially supported, Android Studio.
It turns out the way I used to create tabbed applications is now deprecated, so I made this simple template to help with starting future applications.

# Troubleshooting
The following two lines had to be added to the build.gradle file in order to work:

    compile 'com.android.support:appcompat-v7:23.0.0'
    compile 'com.android.support:design:23.0.0'
  
If Android Studio is updated in the future, the above lines could be out of date.
Check in the menu under "Tools>Android>SDK Manager" and then select the SDK Tools tab and make sure the above version numbers are correct.


