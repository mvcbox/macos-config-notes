If you are facing an error like that on new MacOS version.

xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun

It means that you need to install XCode command line, open a Terminal and run this command:

$ xcode-select --install
