# Setup Virtual Robot in Android Studio on macOS

## Installing dependencies
1. Download [git](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/git-2.6.2-intel-universal-mavericks.pkg), [java](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/amazon-corretto-8.302.08.1-macosx-x64.pkg), and [360Controller](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/Install360Controller.pkg).
    > 360Controller WILL NOT install on macOS Big Sur or newer.

2. Run the installers for each.
    > If macOS complains that the installer is not signed by an identified developer, you may need to override it. See [Apple's support page](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/mac) for details.
 
    <details>
    
    ![](resources/install-git.png)
    </details>

## Installing Android Studio
1. Download the [Android Studio installer](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/android-studio-2020.3.1.23-mac.dmg).
2. Open the installer, and drag the "Android Studio" icon into the "Applications" folder. **ONLY DO THIS ONCE!** Close the installer.
    <details>
    
    ![](resources/drag-android-studio.png)
    </details>

4. Open the newly installed Android Studio app.
    > See [Open Apps and Documents on Mac](https://support.apple.com/guide/mac-help/open-apps-and-documents-mchlp1014/10.14/)
5. In the setup helper, select the "Standard" installation type. Leave all of the default settings.

## Loading the Virtual Robot project
1. In Android Studio, select "Get from VCS".
    <details>
    
    ![](resources/get-from-vcs.png)
    </details>
2. Select the GitHub tab.
3. Add a GitHub token
    1. Select "Use token..."
        <details>
        
        ![](resources/use-token.png)
        </details>
    2. Select "Generate..."
    3. It will open the GitHub token creation page.
    4. Leave everything the same except the **Expiration**, set this to *"No expiration"*. You may need to change the **Note** section if you have another token with the same name.
        <details>
        
        ![](resources/setup-token.png)
        </details>
    5. Scroll to the bottom and select "Generate token".
    6. Copy the resulting token (`ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX`).
        <details>
        
        ![](resources/copy-token.png)
        </details>
    7. In Android Studio, paste this token and click "Log In".
4. In the list of repositories, select `panthera2021/virtual_robot`.
5. Click "Clone".