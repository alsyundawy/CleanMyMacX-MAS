# CleanMyMac X

Unlock (almost) all CleanMyMac X's features for free!

Updated to version 4.12.6 (App Store) - Intel Chip

Apple Silicon is not supported.

## How to use

1. Open a terminal window and navigate to the directory where you want to clone the repository.
2. Type `git clone https://github.com/davidepedrazzi/CleanMyMacX.git` and press enter to download the repository to your computer.
3. Type `cd CleanMyMacX` and press enter to navigate to the CleanMyMacX directory.
4. Type `chmod u+x patch.py` and press enter to make the patch.py file executable.
5. Type `sudo ./patch.py` or `sudo python3 ./patch.py` and press enter to run the tool.

Expected output:

```
$ sudo ./patch.py
Patching /Applications/CleanMyMac-MAS.app/Contents/MacOS/CleanMyMac-MAS...
Patching /Applications/CleanMyMac-MAS.app/Contents/Library/LoginItems/CleanMyMac-MAS Menu.app/Contents/MacOS/CleanMyMac-MAS Menu...
Re-signing /Applications/CleanMyMac-MAS.app...
/Applications/CleanMyMac-MAS.app: replacing existing signature
/Applications/CleanMyMac-MAS.app: valid on disk
/Applications/CleanMyMac-MAS.app: satisfies its Designated Requirement
Enjoy!
```

## TODO

- Parse Objective-C metadata
- Warn the user if the app has already been patched (optional)
- Unlock missing features
- Hide 'Unlock Full Version' button in menu
- Add support for Apple Silicon

## Read me

Before opening an issue, delete the app and re-download it from the App Store.<br>In most cases it will fix the problem.
