<p align="center">
  <img src=".assets/sdk2013ce.png" width="200" height="200">
</p>

<div align="center">

 <a href="">[![Multiplayer Win](https://github.com/Nbc66/source-sdk-2013-ce/actions/workflows/MP_windows.yml/badge.svg)](https://github.com/Nbc66/source-sdk-2013-ce/actions/workflows/MP_windows.yml)</a>
<a href="">[![Singleplayer Win](https://github.com/Nbc66/source-sdk-2013-ce/actions/workflows/SP_windows.yml/badge.svg)](https://github.com/Nbc66/source-sdk-2013-ce/actions/workflows/SP_windows.yml)</a>

</div>

# Source SDK 2013 Community Edition
Source 2013 CE is a clean fork of Valve's [Source SDK 2013 repo](https://github.com/valveSoftware/source-sdk-2013) 
with the goal of fixing up the SDK and to provide a clean bloat-free codebase that works out of the box to make developers' lives easier.

# Info
There are currently two branches, the first one being `master` which will only contain fixes without any extra additions.</br>
The second one is `Experimental` which is the branch we use to add new features and helpful tools for developers.</br>
And a third branch `enhancements` soon to appear, which will include some neat features that we think you will enjoy, 
some made by the community, some backported from other engine branches such as Alien Swarm, and everything in-between.

You can find Source 2013 CE's roadmap by going to our [Trello board](https://trello.com/b/MOxQ2iai/source-sdk-2013-community-edition).

And you can also give us suggestions for fixes and features that you'd like to see in our Discord channel (`#source-SDK-2013-ce`) found in the 
Source Modding Community server, which you can join [here](https://discord.gg/BD6WpY5).

# Compiling

## Compiling on Windows
1. Install **Visual Studio 2019**
2. Install dependencies:
  * MSVC v142 - VS 2019 C++ x64/x86 build tools
  * C++ MFC Library for latest v142 build tools (x86 and x64)
  * Windows 11 SDK (10.0.22000.0)
3. Navigate to the source directory (`sp/src` or `mp/src`)
4. Generate the project files, use `createallprojects.bat` or `creategameprojects.bat`
5. Open `Everything.sln` or `Game.sln`
6. Build the project by clicking on "BUILD" on toolbar
7. Click on "Build Solution"
8. Locate the compiled mod(s) in the game folder

## Compiling on Linux
1. Install dependencies:
    Debian/Ubuntu: `apt-get install build-essential gcc-multilib g++-multilib`
    Arch Linux: `pacman -S base-devel multilib-devel`
2. Navigate to the source directory (`sp/src` or `mp/src`)
3. Generate the project files, use `createallprojects` or `creategameprojects`
4. Build the project `make -f Everything.mak # or make -f Game.mak`
5. Locate the compiled mod(s) in the game folder

# Contributing
We appreciate any form of help so ideally if you want to help this project out the best way would be to make a pull request.

# Ending Notes
Thank you for trying out this project we hope we will help you out with your Source engine troubles!

Made with :heart: by [@Nbc66](https://github.com/Nbc66) & [@GamerDude27](https://github.com/GamerDude27)

Credits for 2019 support: momentum mod, Brae, and Anthonypython
Credits for CI: TF2Vintage, Deathreus, Dio, Anthonypython
