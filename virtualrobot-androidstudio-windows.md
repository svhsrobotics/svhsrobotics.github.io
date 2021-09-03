# Setup Virtual Robot in Android Studio on Windows

## Installing dependencies
1. Download [git](https://github.com/panthera2021/panthera2021.github.io/releases/download/virtualrobot-androidstudio-windows/Git-2.33.0.2-64-bit.exe) and [java](https://github.com/panthera2021/panthera2021.github.io/releases/download/virtualrobot-androidstudio-windows/amazon-corretto-8.302.08.1-windows-x64-jdk.msi)

2. Run the installers for each. Leave all of the settings as their defaults.

    ![](assets\images\virtualrobot-androidstudio-windows/corretto8-install.png)

## Installing Android Studio
1. Download the [Android Studio installer](https://redirector.gvt1.com/edgedl/android/studio/install/2020.3.1.24/android-studio-2020.3.1.24-windows.exe).
2. Open the installer. Leave all of the settings as their defaults.

    ![](assets/images/virtualrobot-androidstudio-windows/install-androidstudio.png)

4. Open the newly installed Android Studio program.
5. In the setup helper, select the "Standard" installation type. Leave all of the default settings.

    ![](assets/images/virtualrobot-androidstudio-windows/androidstudio-download-components.png)


## Loading the Virtual Robot project
1. In Android Studio, select "Get from VCS".
    ![](assets/images/virtualrobot-androidstudio-windows/get-from-vcs.png)
2. Select the GitHub tab.
3. Add a GitHub token
    1. Select "Use token..."
        ![](assets/images/virtualrobot-androidstudio-windows/use-token.png)
    2. Select "Generate..."
    3. It will open the GitHub token creation page.
    4. Leave everything the same except the **Expiration**, set this to *"No expiration"*. You may need to change the **Note** section if you have another token with the same name.
        ![](assets/images/virtualrobot-androidstudio-windows/setup-token.png)
    5. Scroll to the bottom and select "Generate token".
    6. Copy the resulting token (`ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX`).
        ![](assets/images/virtualrobot-androidstudio-windows/copy-token.png)
    7. In Android Studio, paste this token and click "Log In".
4. In the list of repositories, select your fork of virtual robot (`virtual-robot` or similar).
    > It is recomended that you clone your own *personal* fork, not the `panthera2021/virtual-robot` repo because you need to do the tutorial by yourselves.
6. Click "Clone".