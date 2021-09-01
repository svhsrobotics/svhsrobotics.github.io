# Virtual Robot Setup Instructions for macOS
### All downloads can be found on the [downloads page](https://github.com/panthera2021/setup-instructions-mac/releases/tag/downloads) for this repo.

## Sign up for GitHub
1. Go to the [GitHub signup page](https://github.com/signup).
2. Follow the instructions.
3. Request access to the panthera2021 organization. (email someone in the group with your username)

## Installing dependencies
1. Download [git](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/git-2.6.2-intel-universal-mavericks.pkg), [java](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/amazon-corretto-8.302.08.1-macosx-x64.pkg), and [360Controller](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/Install360Controller.pkg).

2. Run the installers for each.
    > If the package refuses to open, control-click on the file and click "Open" in the context menu to force it.
 
    <details>
    
    ![](https://user-images.githubusercontent.com/53275876/131587027-d9180144-d721-4688-bb9c-5d56aac81d56.png)
    </details>

## Installing Android Studio
1. Download the [Android Studio installer](https://github.com/panthera2021/setup-instructions-mac/releases/download/downloads/android-studio-2020.3.1.23-mac.dmg).
2. Open the installer, and drag the "Android Studio" icon into the "Applications" folder. **ONLY DO THIS ONCE!** Close the installer.
    <details>
    
    ![Screen Shot 2021-08-31 at 7 13 45 PM](https://user-images.githubusercontent.com/53275876/131587546-fdeaadbd-9353-456b-81ef-ad1bd6f59f7d.png)
    </details>

4. Open Finder and navigate to your "Applications" folder. Open Android Studio.
    <details>
    
    ![Screen Shot 2021-08-31 at 7 16 16 PM](https://user-images.githubusercontent.com/53275876/131587768-22c3f0d7-9168-4f1f-9a53-95e8ef5a3b2d.png)
    </details>

5. In the installer, select the "Standard" installation type. Leave all of the default settings.

## Loading the Virtual Robot project
1. Open Android Studio (from the Applications folder)
2. Select "Get from VCS"
    <details>
    
    ![Screen Shot 2021-08-31 at 7 34 22 PM](https://user-images.githubusercontent.com/53275876/131589536-175867af-e4f4-4f5b-bf1d-95cebcaf4b89.png)
    </details>
4. Select GitHub
6. Add a GitHub token
    1. Select "Use token..."
        <details>
        
        ![Screen Shot 2021-08-31 at 7 35 10 PM](https://user-images.githubusercontent.com/53275876/131589566-5c8d53dc-fdf2-48b3-a26f-eac2b0ff469c.png)
        </details>
    3. Select "Generate..."
    4. It will open the GitHub token creation page.
    5. Leave everything the same except the **Expiration**, set this to *"No expiration"*. You may need to change the **Note** section if you have another token with the same name.
        <details>
        
        ![Screen Shot 2021-08-31 at 7 38 02 PM](https://user-images.githubusercontent.com/53275876/131589830-6559a1f0-a058-4631-aa98-4975d6973d2e.png)
        </details>
    7. Scroll to the bottom and select "Generate token".
    8. Copy the resulting token ("ghp_...").
        <details>
        
        ![Screen Shot 2021-08-31 at 7 41 10 PM](https://user-images.githubusercontent.com/53275876/131589870-b498566f-c36f-4983-9b36-b199a94cb227.png)
        </details>
    10. In Android Studio, paste this token and click "Log In".
7. In the list of repositories, select `panthera2021/virtual_robot`.
8. Click "Clone".
