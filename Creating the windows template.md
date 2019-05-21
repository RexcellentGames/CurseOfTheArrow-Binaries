## Pre-requests:
- Download the `win32.zip` and `win64.zip` builds of LÖVE from https://love2d.org
- Download the [Resources Hacker](http://www.angusj.com/resourcehacker/)
- Create the `.ico` icon, check the [Creating the icon](https://github.com/RexcellentGames/CurseOfTheArrow-Binaries/blob/master/Creating%20the%20icon.md) guide.

## Instructions:
1. Extract the LÖVE build `.zip`
2. Replace `love.ico` and `game.ico` with the game's `.ico` (rename it to each file name)
3. Delete `lovec.exe`, `changes.txt` and `readme.md`
4. Rename `license.txt` to `LOVE-license.txt`
5. Place your game license as `GAMENAME-license.txt`
6. Rename `love.exe` to the name you wish
7. Open the executable with the resources hacker
8. Open the `Icon Group` folder, right click the first item and select `Repalce Icon`
9. After replacing the icon successfully, open the `Version Info` folder
10. Change the values as you want, but leave the version number alone
11. Save the modified executable
12. Zip the folder content, without a wrapping directory, and upload into github releases
