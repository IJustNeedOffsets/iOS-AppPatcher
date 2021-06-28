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
"./AppPatcher /Drag/Folder/With/Multiple/iPA´s/Here/"
After you installed a merged ipa, the apps will not show up on your home screen, reboot or respring your idevice to let them appear.

# Installing

To install the ipa, simply sign it with whatever tool you want. (I recommend to use AltStore or Signulous, both working perfectly for me)
If you have a jailbreak, the next script will be able to install the ipa by using the tweak appinst from karens repo. (https://cydia.akemi.ai/)
But i think its not making sense to install this patched ipa with Appsync since its only going to work in jailbroken mode than, while you could use Filza to access the Application.
#IMPORTANT
Make sure the .ipa file doesn´t contain any spaces! (If the ipa is named "Example Patch" rename it to "ExamplePatch")
