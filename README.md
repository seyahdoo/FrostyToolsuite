# FrostyToolsuite
The most advanced modding platform for games running on DICE's Frostbite game engine.

# Why Fork
This fork is specially for 1.0.7 release, since the original creators have written this code but never released as pre-release.

# Building
This person from reddit has a more detailed steps for building, so im just quoting their message here;

```
You have to build 1.0.7 yourself.

    Clone the official Frosty repo: github/CadeEvs/FrostyToolsuite/1.0.7 (follow their instructions, or use github desktop, anything works)

    Install/Modify Visual Studio 2019-2022, and make sure to have both .NET and C++ desktop development selected, and on the right check Windows 10 SDK 10.0.18362.0

    Open .\FrostyToolsuite\FrostyEditor\FrostyEditor.sln inside the directory you cloned the repository into.

    DO NOT click the green triangle, instead in the Solution Explorer tab on the right (if it isn't there, Ctrl+Alt+L), right click Frosty Editor, and Build

    If it fails, individually build everything except for the Editor and ModManager, and then you should be able to build the Editor and MM (if it still fails, look at the error message, it'll tell you if it needs something to be built before it)

    In the Solution Explorer, right click and Build the Plugins folder (Keep an eye out for errors here as well, you should get 26 normal + 6 fifa plugins at the end)

How to use:

    Editor: .\FrostyToolsuite\FrostyEditor\bin\Developer\Debug\FrostyEditor.exe

    MM: .\FrostyToolsuite\FrostyModManager\bin\Developer\Debug\FrostyModManager.exe

    Origin: github/p0358/F_off_EA_App

To the Frosty team: Please publish a beta build for 1.0.7, since it's necessary for NFS UB, and works well enough. People downloading others' build is really sketchy. They can just copy paste in a C# or C++ malware into any of the projects, and spread it. This has happened in the CSGO hvh community a lot before with prebuilt Osiris dlls, and updated cracked dlls, shipping with dc token stealers, rats, and miners.

```


https://www.reddit.com/r/needforspeed/comments/13n9r6b/comment/joyh1qw/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button

## Setup

1. Download Git https://git-scm.com/download/win.
2. Create an empty folder, go inside it, right click an empty space and hit "Git Bash Here". That should open up a command prompt.
3. Press the green "Code" button in the repository and copy the text under "HTTPS".
4. Type out ``git clone -b <branch_name> <HTTPS code>`` in the command prompt and hit enter. This should clone the project files into the folder.
5. Open the solution (found under FrostyEditor) with **Visual Studio 2019**, and make sure the project is set to ``DeveloperDebug`` and ``x64``. Close out of retarget window if prompted.
6. Only build the projects themselves, never the solution.

## License
The Content, Name, Code, and all assets are licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.
