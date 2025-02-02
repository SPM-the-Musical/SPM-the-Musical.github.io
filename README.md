<script src="https://cdn.jsdelivr.net/gh/ncase/nutshell/nutshell.js"></script>
<script>
Nutshell.setOptions({
    startOnLoad: true,
    lang: 'en',
    dontEmbedHeadings: true,
});
</script>

# Welcome!
This is the unofficial website for Super Paper Mario the Musical!

Newest video:
[:Fracktail Battle](https://www.youtube.com/watch?v=BaaAlXHtDZg)

# What is SPMtM?
SPMtM is a YouTube series created by Game Rec Room, a talented group of artists, lyricists, and singers. It is a full lyrical adaptation of [:Super Paper Mario](https://en.m.wikipedia.org/wiki/Super_Paper_Mario), with 8 songs currently released and 42 more planned!

# Can I help?
The answer depends on what exactly you want to help with. To find out, you should DM @Coolskeleton95. on Discord, or join the [Game Rec Room Discord server](https://discord.com/invite/G3sxEaBPJR) and ask him there!

# Can I put songs from SPMtM into the game?
Yes... but there are two problems.
First, the Game Rec Room team worked very hard on this musical, so please at least subscribe to their channel before downloading their music. Every view counts, especially on smaller channels.
The second problem is less serious, but still important: this is a complicated process, so proceed with caution, especially if you're not tech-savvy. 

# How to add custom songs to Super Paper Mario

## This tutorial assumes you don't have Dolphin Emulator or a Super Paper Mario ROM downloaded. If you already do have those setup on your PC, the only step you should skip is installing the emulator. 

## And don't worry, if you have save data for Super Paper Mario, this process will not mess it up.

## First, you need to download some stuff. 
Download the [Dolphin Emulator](https://dolphin-emu.org/download/), the [SPM Randomizer](https://github.com/skawo/Super-Paper-Mario-Level-Editor-Randomizer/release) (don't worry, you don't have to randomize the game for this to work), and a [Super Paper Mario ROM](https://myrient.erista.me/files/Redump/Nintendo%20-%20Wii%20-%20NKit%20RVZ%20[zstd-19-128k]/Super%20Paper%20Mario%20%28USA%29%20%28Rev%202%29.zip). If you don't already have the song you want downloaded, download that as well. 

## Optionally, increase your song's volume.
Super Paper Mario's sound files are fairly loud so they can be heard over the sound effects. If you need to increase your song's volume, I recommend [audioalter.com/volume](https://audioalter.com/volume). Just move the slider to the right until you reach the right volume.

## Next, you have to speed up your song.
Super Paper Mario handles music very weirdly: the songs are sped up to be twice as fast as normal, which saved storage space for the developers but is now causing problems for us. Go to [audioalter.com/tempo](https://audioalter.com/tempo) and drag the slider all the way to the right to set it to 2x speed. Make sure to uncheck the box labeled "preserve pitch". 

## Now, you have to convert your music into a format the game understands. 
Super Paper Mario uses an audio format called "BRSTM", which is not a normal file type. Thankfully, some people on the internet have made it easy for us to change mp3s to BRSTMs.
Go to the website [mu-wave BRSTM Maker](https://kazuki-4ys.github.io/web_apps/mu-wave/). Click the big button in the center of the screen and optionally drag the arrows around to trim the audio. If you're changing background music, make sure to check the "Loop?" checkbox and set the loop's starting point. Once you're satisfied, download the BRSTM file from mu-wave and give it a temporary name, it doesn't matter what for now.

## Once you've got the audio, you have to set up the game and the emulator it runs on.
Start up Dolphin Emulator by unzipping the zip folder and double-clicking "dolphin.exe". If you haven't already, Dolphin will prompt you to pick a location to store your games. I recommend making a new folder inside the Dolphin Emulator folder, just so it all stays self-contained and you're less likely to accidentally delete your games. 

## After you set up Dolphin, you have to change your file to an iso.
If your game is on the main screen of Dolphin Emulator, right-click it and select "Convert File", select "ISO" from the drop-down, and click "Convert". This will allow you in the next step to access the game's files by extracting the ISO.

## Time to finally put your custom music into the game!
Now, start up the SPM Randomizer. Click on "File" → "Extract ISO" → your Dolphin game folder → your ISO file. Super Paper Mario's music is located at R8PE01 (this name is slightly different depending on the region you choose; this is the USA version.) → DATA → files → sound. Use [this website](https://kenrick95.github.io/nikku/) to play the BRSTM files there and find the song you want to replace. Change the name of your custom music to the EXACT filename of the song you want to replace, then place it into the "sound" folder! 

## You're almost done...
Start the SPM Randomizer again. Choose "File" → "Pack ISO" → the Super Paper Mario folder, likely R8PE01 (again, this differs between regions). Then choose a name for the new ISO, now with your custom music, and place it into your Dolphin games folder. If you've done everything correctly, you should now be able to start the game through Dolphin Emulator and listen to your custom music!
