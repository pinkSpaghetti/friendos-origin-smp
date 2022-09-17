# Friendos Origins SMP

Using CurseForge is a pain in the ass so I'm switching it up.
The only file you need from here is the .zip file.
You will also need:
 - [Minecraft](https://minecraft.net/) Java Edition, either from the Minecraft website or from the Microsoft Store
 - [CurseForge](https://download.curseforge.com)
 - [Java](https://www.java.com/en/download/) - Not sure if you actually do but better safe than sorry
 - To know how much RAM your PC or laptop has so you can allocate an appropriate amount to Minecraft

## Modpack Setup Guide

Because this isn't going directly through the CurseForge service you need to put in extra effort.

### RAM

If you don't already know how much RAM you have:
1. Press `Ctrl+Chift+Esc` to open Task Manager
2. Click the button in the bottom left that says 'More Details'. if the button says 'Fewer Details' then ignore
3. Go to __Performance__ > __Memory__
4. Your total available memory should be displayed in the top right corner of the window. Remember the number or leave the window open.

If you want more RAM for free then you can Google __Swap Files__ and figure them out yourself.
Ideally, you want to be able to dedicate at least 4GB of RAM to a _modded_ Minecraft instance, and no more than 50% of your total RAM (unless you have a metric shitton of RAM).
If you can't allocate 4GB of RAM to Minecraft it's not a problem but the game will probably be a bit laggy.

### Minecraft

Minecraft needs to be installed, and a version of it needs to be run.
As the current pack is 1.18.2 I would say to run an installation of that version, but running the latest should work too.
Once the instance has launched to the Main Menu you can exit the game

### CurseForge

CurseForge is the modpack manager for you to keep your modpacks organised, assuming you have more than just this one, and away from the vanilla installation.
Once the program is installed and launched:
1. You may need to create an account and login. It should work even if you don't but you might have to.
2. Once you've either read or ignored the startup tours, you should be presented with a __Choose a Game__ page. Choose Minecraft. If you haven't launched a Minecraft instance from the Minecraft launcher yet then it won't be available as an option.
3. In the bottom left corner click __Settings__ > __Game Specific__ > __Minecraft__
4. Scroll down to __Allocated Memory__ and drag the slider to whatever amount you feel is right. The slider is presented in MB, where 1024MB = 1GB, so to get my suggested 4GB drag the slider to 4096MB.
5. Close the __Settings__ page.
6. Click __Create Custom Profile__ in the top right corner of the minecraft tab.
7. Click __import__ a previously created profile.
8. Navigate to wherever you saved the .zip file from this page to, probably your Downloads folder.
9. Click on the .zip file and click open.
10. Once the pack is ready, play it.

If you're planning on playing on or running an SMP server then the URL/IP address should be provided by your server admin or hosting service.

### QOL

If you're playing a Nether origin, such as Blazeborn, then you'll spend a decent chunk of time with half of your screen obscured by fire. To solve this, go to [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs/), __make sure that you select 1.18 as the version__, scroll down to the __Unobtrusive__ tab, and select __Lower Fire__. The website has installation instructions documented themselves. You can also select any other resource packs that you want. There are Connected Textures resource packs but there are mods that take care of that. This is easier than using a server resource pack

## Updating the pack

Updating the pack is kinda funky because the updates aren't getting pushed straight to CurseForge.
There's couple of ways of doing it, you're free to pick whatever sounds easiest.

1. __Reinstallation__. Follow the above steps for installing the pack, using the latest .zip file. Your settings, shaders, and resource packs won't be carried over to the new installation, but this has the least steps involved.
2. __Reinstallation with extra steps__. Import the pack to CurseForge as per my last email, but instead of using this new pack:
    1. __In the newly created pack__ next to the __Play__ button is a "Traffic Light". Click there and go to __Open Folder__.
    2. Right click on the mods folder and copy it.
    3. Open the folder of the Origins pack created, the one that you've been using.
    4. Paste the copied folder into the window that opens. If prompted, select __Replace (all) files in destination__.
3. __DIY, possibly from your DNA__. Open the changelog.md file located in the GitHub repo. All the changes for a given version are documented there. You can then go and add, remove, update mods as per the documentation.

