# iOS-AppPatcher
This is a script to patch .ipa or other Archives which have an .app folder.


# Compiling
You don´t need to compile anything, it´s just a shell script. (This will maybe chnage in future)

# How i randomly "discovered" this.
I was bored and remembered how someone asked me about accessing applications files and I said only possible with jailbreak. When i created an app in xcode and wanted to intigrate it in the Files app, I just thought that you can do integrate any app in the Files app, without source code or needing to program something.

# Usage
AppPatcher can apply patches to an .ipa file to be accessible from the default iOS files app without a jailbreak.
AppPatcher can merge multiple .ipa files to one iPA file. (Make sure to respring or reboot after installing,)

To use this script, run the commands below first:
"cd /DRAG/THE/APP/PATCHER/FOLDER/HERE"
"chmod +x AppPatcher"

Patching an .ipa file to show up in default ios files:
"./AppPatcher /iPA/FILE/HERE/DRAG"

Merging iPA´s
Before merging ipa´s, make a folder and paste all iPA´s you want to be merged in that folder.
"./AppPatcher -b /Drag/Folder/With/Multiple/iPA´s/Here/"
After you installed a merged ipa, the apps will not show up on your home screen, reboot or respring your idevice to let them appear.

# Installing

To install the ipa, simply sign it with whatever tool you want. (I recommend to use AltStore or Signulous, both working perfectly for me)
If you have a jailbreak, the next updates will add an option to install the ipa by using the tweak appinst from karens repo. (https://cydia.akemi.ai/)
But i think its not making sense to install this patched ipa with Appsync since its only going to work in jailbroken mode than, while you could use Filza to access the Application.
#IMPORTANT
Make sure the .ipa file doesn´t contain any spaces! (If the ipa is named "Example Patch" rename it to "ExamplePatch")

# Coming Soon
-UI version when AppPatcher is out of Beta (MacOS and iOS/iPados)
-Hide apps from SpringBoard
-Shoe hidden apps on SpringBoard
-Modify Assets
-Change display name of Application
-Add or Change Url scheme (for example add a url scheme like OpenFromAnyBrowser:// to open the specific application)
-Convert iPA to Deb or Deb to iPA. 
-Something really big to add an installation path to an Application

# Improvements
Please feel free to make Pull Request and forks of AppPatcher
I really like to see people are interested in my work

# Crediting
If you want to include AppPatcher in your program/Tool:
Make your tool on GitHub (closed or open sourced) and add link to my AppPatcher repo instead of including the script.
If you want to make changes to AppPatcher and use it in your program, please ask me on Twitter or Reddit first. (Links below)
If you make a fork of this repo, you can change anything you want without crediting
Make pull request of your modified AppPatcher version. (I'll credit you if i approved the request)
For any other questions feel free to contact me on Twitter or Reddit:
Twitter: https://twitter.com/IUnl0ck1?s=09     (you will likely get an answer faster on Twitter)
Reddit:  https://www.reddit.com/u/Administrative-Fan4?utm_medium=android_app&utm_source=share

# Credits
Me [https://twitter.com/IUnl0ck1?s=09]
To get credited make any changes/improvements or share knowledge which is useful for AppPatcher. (About iOS in gernal)
