# iOS-AppPatcher
This is a script to patch .ipa or other Archives which have an .app folder.


# Compiling
Please be patient, the source code will be uploaded as soon as I have done my .car file patches
Another person on GitHub made a pull request for the source code. He also has a big dick and his name is @spacepilotAV

# How i randomly "discovered" this.
I was bored and remembered how someone asked me about accessing applications files and I said only possible with jailbreak. When i created an app in xcode and wanted to intigrate it in the Files app, I just thought that you can do integrate any app in the Files app, without source code or needing to program something.

# Usage
This script simply patches the app to have its /Documents/ folder accessible in the default file manager, without jailbreak!

To patch an .ipa just open Terminal and cd in the AppPatcher folder. 
"cd /Drag/The/AppPatcher/Folder/here"
Than we need to chmod the executable
"chmod +x AppPatcher"
To apply the patches on the ipa file type:
"./AppPatcher /DRAG/THE/IPA/YOU/WANT/TO/PATCH/HERE"
After it patched the ipa successful it should open a new finder window. In there go in the Tempt/ and there you have the orginal .ipa and the patched.ipa

# Installing

To install the ipa, simply sign it with whatever tool you want. (I recommend to use AltStore or Signulous, both working perfectly for me)
If you have a jailbreak, the next script will be able to install the ipa by using the tweak appinst from karens repo. (https://cydia.akemi.ai/)
But i think its not making sense to install this patched ipa with Appsync since its only going to work in jailbroken mode than, while you could use Filza to access the Application.
#IMPORTANT
Make sure the .ipa file doesn´t contain any spaces! (If the ipa is named "Example Patch" rename it to "ExamplePatch")
