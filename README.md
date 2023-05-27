# Railroad-ModPack
 A bunch of mods that the Railroad Radio crew have tested quite thoroughly and play really well together.
 We do play with a lot of cards disabled, and I wish there was a way to include that with a modpack.

 Wanted to create a modpack where I could do version control for mod updates, and only upgrade when versions are compatible. Specifically so that when I do find a working version upgrade, I don't have to walk every single person through which mods to upgrade.

# Notes on using my disabled/enabled cards
 No card pack is balanced, and I always have a decent amount of cards and maps disabled from each pack I've included in this modpack. Some cards are either too good, terrible, or literally break the game when mixed with other cards.

 Sadly there is not a way to automatically disable cards when downloading a modpack. However, there is a file that keeps track of all enabled/disabled cards and maps. I will now start uploading that to the git repo for this pack for those who want it (just part of the file for cards).

 IMPORTANT:
 If you install additional mods other than this modpack, they will NOT be included in my config. So you would need to follow the steps below BEFORE you install the other mods. Or copy and paste configs that you want for each card pack.

 IMPORTANT:
 If you are going to do this, do it BEFORE you update all. Any updates that include new cards will not exist in my config file when I uploaded it.

# How to use my enabled/disabled cards and maps
Go to the git repo https://github.com/Lencalotp/Railroad-ModPack for this project, and download the UnboundLib_JustCards.CFG file.

In r2Modman, go to Settings -> Locations -> Browse profile folder

In your file explorer go to BepInEx/config/

Personally, Id copy your old UnboundLib file and save a copy of it as UnboundLib_old just in case.

In your file search for "[Level categories]"

Replace everything above this line with the contents of the .cfg you downloaded. (save)

Now all of the cards I have disabled should also be disabled for you when you boot up rounds.

### Version 0.2.0
  Removing some card packs we always have disabled

  Uploading my config for cards and maps

### Version 0.1.5 - Some Changes
  Removing:
    YetMoreCards
    ChaosPoppycarsCards
    PoppyPlaytimeCards

  Adding:
   Arcana
   KeysCards
   VarietyCards
   WillsWackyGameModes

### Version 0.1.4 - removing HDC and CommitmentCards adding PoppyPlaytimeCards
  The dino cards from HDC were too strong, ended up playing with all but 1 or 2 of them disabled. Just removing the whole pack.
  Likewise with commitmentcards, really liked distill and copy, but everything else was too strong.

  Adding PoppyPlaytimeCards to give it a try.

### Version 0.1.3 - removing FFC
  FFC is breaking other card packs because it uses an older version of class manager, removing it.

### Version 0.1.2 - Upgrading to versions
  Removed DullNevCards, added MadCards. Upgraded everything to most recent.

### Version 0.1.1 - First upload
  Current Mod versions are working well, Its the most stable game of rounds we have had in a long time.

  Just added the CR card pack however, and have noticed some of the CR cards can drasticaly decrease performance and cause crashes with the right pairings. But disabling the CR cards, the game will be really stable.
