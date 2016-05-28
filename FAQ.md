# Frequently asked questions



## I try to open a file with the menu File->File Open... and only get an Error

This is a known issue with versions pre 0.8.3 when trying to open external files outside of Eclipse via the menu command File->File Open...

You can upgrade to version 0.8.3 or make sure the mod file is opened from an Eclipse project as per the tutorials.

## The tool sounds great but I don't want to use Eclipse!

That is your choice. This plugin will only be supported for Eclipse. Best of luck.

## I can't get Eclipse to work!

I'm sorry to hear this. This is a moderately advanced tool and may be beyond some modders capabilities. Feel free to contact me on the Sins forum if you think you are close and just need assistance getting over the hill.

## Why don't I see any validation errors?

Is the Sins Eclipse PlugIn installed? You can verify this by right clicking on the project and checking if "Add/Remove Entity Validator" is visible.

If you don't see this option please ensure you have properly installed the plugin (InstallPlugin).

If the option is visible then make sure you select "Add/Remove Entity Validator".


## I added a bunch of Particle Effects, why do they still show up as warnings in the entity file?

### Option 1

This is an early version of the tool and some changes are not automatically registered such as this. Selecting the menu option Project->Clean... will revalidate all the entity files.

### Option 2

Upgrade to the latest version (v0.8.2 or later). The newer versions have resource listeners that automatically rebuild the project under certain situations.


## I've installed the Plugin, why does everything show as an error?

Are you preferences set correctly for the Sins reference files? You can check by selecting the menu option Window/Preferences and verifying against Sose Preferences.

![http://dl.dropbox.com/u/5790092/SinsTools/Sose_preferences2.jpg](http://dl.dropbox.com/u/5790092/SinsTools/Sose_preferences2.jpg)

**The tool is expecting the Sins files such as GameInfo, Sound, etc to be located in the root of the directories specified, this applies to the project mod folder as well.**

## I can't get the tool to work, but that's b/c I have absolutely no experience with java....  How do you install it?

No Java experience is required. The core part of this plugin is simply a validation tool that sits on top of the Eclipse text editor. The ant tasks are purely optional and also don't require any java experience.

Did you follow these steps?

[InstallEclipse](InstallEclipse.md)

[InstallPlugin](InstallPlugin.md)

## I'm running a new, Vista 64 bit Home Premium, and the Java is version 6 and the Eclipse is the latest version of the 64 bit classic version.  I haven't bothered downloading the tool yet, b/c I can't get the Eclipse program to work yet.

Eclipse on Windows 64 bit systems requires a download of the 64 bit Java 1.6 and the 64 bit Eclipse tool.

[InstallEclipse](InstallEclipse.md)

## How does content assitance work?

[ctrl](ctrl.md) + [bar](space.md) activates content assitance.

## Why is this better than Notepad++?

Notepad++ is a good tool for text editing. However, Eclipse contains all of the features of Notepad++ plus a lot more. Further Eclipse is an industry standard for software development including many advanced features for managing a project.

The Sins of a Solar Empire Eclipse Plugin adds to this functionality by providing features that could never be included in Notepad++ (excluding syntax coloring).

The Sins Editor plugin adds Hover support, content assistance, syntax validations, and syntax coloring as examples that Notepad++ will never match.

## What am i supposed to take extra courses so i can learn how to mod just to have some fun with this game?

This is a fan made plugin for Eclipse to support moderate to advanced Sins of a Solar Empire mods. It's usage is not required, and in fact I would recommend starting with the wiki and Notepad++ if you are new to modding sins. The wiki is a conversion of my validation rules to the wiki syntax.
