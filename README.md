Specorgi is a mod for Spelunky HD by Mossmouth that replaces the pug damsel with a corgi. I've tried to stay as true to the original art style as I could.

![specorgi
screenshot](https://raw.github.com/jackiekircher/specorgi/master/preview.png "specorgi preview")


###One-step Installation:

If you don't want to deal with downloading the Speluny Modding tool and
unpacking/repacking textures, then follow this one-step installation. The primary
drawback is that you won't be able to install more than just this mod using this
method. For combining mods please see the multi-step installation instructions.

**Make sure to backup the `alltex.wad` and `alltex.wad.wix` files in the
`/Data/Textures`
   directory of your Spelunky installation path.**

Once you've backed them up, replace these files with the `alltex.wad` and `alltext.wad.wix` files for the mod.



###Multi-step Installation:

If you already have mods installed then you can choose to just overwrite individual sprite sheets within the texture files of the game, but the process is a bit more complicated.

**Make sure to backup the `alltex.wad` and `alltex.wad.wix` files in the
`/Data/Textures`
   directory of your Spelunky installation path.**

1. Download the Spelunky Modding tool at http://mossmouth.com/forums/index.php?topic=3637.0

2. Follow the directions in the thread and extrat the contents of alltex.wad using either
   the command line script or the batch files.

3. In the extracted alltex folder, replace `ATSTART/journalmons.png`
with `journalmons.png`,
   and `MONSTERS/monstersbig3.png` with `monstersbig.png`
   * note, if you are already using mods that alter these files they will be overwritten.
     please feel free to merge the specorgi files with other mods you have using any image
     manipulation program that can save png files.

4. Repack the alltex folder with `spelunktool -c alltex` or dragging it
onto the `repack.bat`
   file.

---------------------------


Run Spelunky and have fun!
