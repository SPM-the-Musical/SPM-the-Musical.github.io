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

Latest video:
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

### This tutorial assumes you don't have Dolphin Emulator or a Super Paper Mario ROM downloaded. If you already do have those setup on your PC, the only step you should skip is installing the emulator. 

### And if you have save data for Super Paper Mario, don't worry. If you do it correctly, this process will not change your save data at all. 

### First, you need to download some stuff. 
Download the [Dolphin Emulator](https://dolphin-emu.org/download/), the [Super Paper Mario HD Music mod](https://drive.google.com/file/d/1XHvVyVl5yz8epFRV66vWjbL7cuMbxGbQ), and a [Super Paper Mario ROM](https://myrient.erista.me/files/Redump/Nintendo%20-%20Wii%20-%20NKit%20RVZ%20[zstd-19-128k]/Super%20Paper%20Mario%20%28USA%29%20%28Rev%202%29.zip). If you don't already have the song you want downloaded, download that as well. If you want something from a YouTube video, I recommend using [EZmp3](https://ezmp3.cc). 

### Then you have to set up the game and the emulator it runs on. 
Start up Dolphin Emulator by unzipping the zip folder and double-clicking "dolphin.exe" (or whatever type of executable if not on Windows). If you haven't already, Dolphin will prompt you to pick a location to store your games. I recommend making a new folder inside the Dolphin Emulator folder, just so it all stays self-contained and you're less likely to accidentally delete your games. 

### After you set up Dolphin, you need to use the HD Audio mod to easily change the in-game music.
Unzip the HD Audio mod's folder and remember where you put the contents. Then go back to Dolphin, right-click on Super Paper Mario, and select "Start with Riivolution Patches". Dolphin will tell you to find an xml file, so go to the HD Audio mod folder → Riivolution → SPMHDSound.xml. Click "save as preset", give it a title of your choosing, and save this to your Dolphin games folder. 

### Now, you have to convert your music into a format the game understands. 
Super Paper Mario uses an audio format called "BRSTM", which is a weird file type. Thankfully, some people on the internet have made it easy for us to change mp3s to BRSTMs.
Go to [mu-wave BRSTM Maker](https://kazuki-4ys.github.io/web_apps/mu-wave/), click the big button in the center of the screen, and optionally drag the top-right arrow around to trim the audio. If you're changing background music, make sure to check the "Loop?" checkbox and set the loop's starting point by dragging the top-left arrow. Once you're satisfied, download the BRSTM file and give it a temporary name.

### Time to finally put your custom music into the game!
Use [this website](https://kenrick95.github.io/nikku/) to play the BRSTM files in the SPMHDAudio folder of the HD Audio mod and find the song you want to replace. Change the filename of your custom music to the EXACT filename of the song you want to replace, then move it to the "SPMHDAudio" folder! If you've done everything correctly, you should now be able to start the game through your custom-named game file in Dolphin and listen to your custom music! Conveniently, you can also easily play with the default music by starting the game file with the default name.
