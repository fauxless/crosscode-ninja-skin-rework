# crosscode-ninja-skin-rework-main
Overwrites nearly all of the original textures for Lea with textures befitting of the Ninja Skin DLC. Requires DLC to work properly.
Please note that I am not at all a professional pixel artist, so some of these textures could use some more work. In any case, if you feel you want to make some changes, you absolutely can.

# Explaining what this does #
This is a simple mod that tries to better integrate the Ninja Skin DLC into CrossCode. _Almost_ all of the textures have been paletted over to fit the style and general theme of the Ninja Skin. This even includes facial expressions, all of which have been redone. There is also some modifications to dialogue that reflect characters' reactions to Lea's skin.
Please keep in mind that in the mods current state, not every texture is replaced -- there are a few, predominately from the "A New Home" DLC that still need to be done. 

# Preventing Piracy #
Obviously, I can't just _give_ all of the files from the Ninja Skin DLC for you to download and use. Although that would be more convenient for installation, that would also be piracy. As a result, you will have to supply the main "entity/player" files from the main DLC in order to get the full experience. There will be a guide below on how to do that on Steam; the process should be fairly similar if you own the game from another digital storefront. All it requires is locating the game files on your PC.

# Requirements #
You're going to need CCLoader to install this mod, unless you want to manually inject each and every file (including the code changes) into your game's directory. If that's what you would rather do, then more power to you. But for the rest of you, install CCLoader using the installation guide below:
https://www.youtube.com/watch?v=kY3_C2D2gDA

For all intensive purposes, I recommend using CCLoader to save time instead of installing all of the asset replacements.

You also will need a file archiver program, such as WinRAR or 7Zip. Chances are you likely already have a program like these on your computer if you have ever downloaded a _.zip_ file before.

# Installation Guide #

_STEP 0: Make sure you have CrossCode and the DLC installed!

**1. Clone / download the _.zip_ file from this repository under the 'Release' section.**

**2. Extract the downloaded file to somewhere you can easily access it, such as your desktop.**

**3. Locate your CrossCode directory. On Steam, you can do this by right-clicking on the games' listing in the Library section, going to Properties, clicking on Local Files and finally pressing the _Browse...__ button.**

**4. Navigate to the following directory within the folder you just opened:**
> assets\extension\ninja-skin\media\entity\player\skins

You are looking for something like this:
![image](https://user-images.githubusercontent.com/100042637/156285809-c2ad4437-7690-40f8-a94d-48081256fb60.png)

**5. Copy the two files listed in the image above.**

**6. Next, go back to the _.zip_ file you extracted, and navigate to the following directory:**
> assets\media\entity\player

You should see something like this:
![image](https://user-images.githubusercontent.com/100042637/156286268-0c46e25c-605b-42a3-8a57-feec829e8a42.png)

**7. Paste or drag in the files from the Ninja DLC into this folder.**

Note: For the "A New Home" DLC, you will also need to add the __sleeping.png__ file in this folder as well.

**8. Rename these textures to overwrite the _move.png_ and _throw.png_ respectively. You want the name to be identical to what these two files are.**
Your going to have to remove the original files you're replacing before you can do this step.

**9. Drag the entire folder of the mod into the following directory in your CrossCode folder:** 
> assets\mods

And you are done!

_Optional: If you want to give this mod file a .ccmod extension, you can do that by right-clicking on the folder, clicking "Add to Archive..." and changing the extension in the Archive Name to .ccmod._

Of course, in order to prevent piracy, please do not share your finished product of this mod with anyone else, unless they own the Skin. Radical Fish is an indie studio, so let's do our best to support their work in the future.

That's it! Enjoy!

# Updates

1.0.1 - 2022 / 3 / 14 - Added new dialogue in intro scene, as well as modified it to make it sound betterish.

1.0.2 - 2022 / 3 / 16 - Updated textures for the following files: lea-panic.png, lea-special.png

1.0.3 - 2022 / 3 / 17 - Updated readme + Retextured the following files: lea-hand.png, hugging.png

1.0.4 - 2022 / 3 / 19 - Added textures for sleeping.png, as well as made small modifications for the "A New Home" DLC

1.0.5 - 2022 / 5 / 19 - Added dependencies in package.json (Thank you to the CC Modding server for pointing this out!)

1.0.6 - 2022 / 6 / 1  - Merged pull request that should fix issues with package.json (Greatly appreciated)

1.0.7 - 2022 / 8 / 11  - Created a proper release and updated the readme. No new files have been added.

1.0.8 - 2022 / 8 / 17  - Potentially fixed an issue with loading into Rookie Harbour. If there's further issues with this area let me know.

1.0.9 - 2023 / 1 / 25  - Fixed crash in Rookie Harbor, retextured lea.png
