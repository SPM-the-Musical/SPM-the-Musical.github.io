<script src="https://cdn.jsdelivr.net/gh/ncase/nutshell/nutshell.js"></script>
<script>
Nutshell.setOptions({
    startOnLoad: true,
    lang: 'en',
    dontEmbedHeadings: true,
});
</script>

<link rel="stylesheet" href="stylesheet.css">

<p align="center">
  <img src="https://github.com/SPM-the-Musical/SPM-the-Musical.github.io/blob/main/spmtm%20logo%20HD.png?raw=true" width="550">
</p>

# Welcome to the unofficial website for Super Paper Mario the Musical!
Latest video: [:Merlee's Mansion](https://youtu.be/rsogzZ3Pzn8)

# What is Super Paper Mario the Musical?
Super Paper Mario the Musical is a YouTube series created by Game Rec Room, a talented group of artists, lyricists, and singers. It is a full lyrical adaptation of [:Super Paper Mario](https://en.m.wikipedia.org/wiki/Super_Paper_Mario), with 10 songs currently released and 40 more planned!

# Can I help?
The answer depends on what exactly you want to help with. To find out, you should DM @Coolskeleton95. on Discord, or join the [Game Rec Room Discord server](https://discord.com/invite/G3sxEaBPJR) and ask him there!

# Can I put songs from the musical into the game?
Yes... but there are three issues.

First, the Game Rec Room team worked very hard on this musical, so please at least subscribe to their channel before downloading their music. Every view counts, especially on smaller channels.

Second, this is a mildly complicated process, so proceed with caution if you're not tech-savvy.

Third, this tutorial is for Dolphin Emulator only. I'm sure you can do this on a real Wii, but I don't know how.

# How to add custom songs to Super Paper Mario

## First, you need to download some stuff. 
Download [Dolphin Emulator](https://dolphin-emu.org/download/) (if you don't have it installed already), the [Super Paper Mario HD Music mod](https://drive.google.com/file/d/1XHvVyVl5yz8epFRV66vWjbL7cuMbxGbQ), and a [Super Paper Mario ROM](https://myrient.erista.me/files/Redump/Nintendo%20-%20Wii%20-%20NKit%20RVZ%20[zstd-19-128k]/Super%20Paper%20Mario%20%28USA%29%20%28Rev%202%29.zip). You also need to download the song you want as a music file (.mp3, .wav, or .ogg). If you want a song from a YouTube video, I recommend using [AnyUkit YouTube to WAV Converter](https://anyukit.com/youtube-to-wav/). 

## Then you have to set up the game and the emulator it runs on. (Skip this step if you already have Dolphin installed.)
Start up Dolphin Emulator by unzipping the zip folder and double-clicking the file called "Dolphin.exe" (or the usual type of executable/app file if you're not using Windows). If you haven't already, Dolphin will ask you to pick a location to store your games. I recommend making a new folder called "ROMs" that you can place all your emulator games into. Once you've decided where to put your ganes, put your Super Paper Mario ROM into that folder. 

## After you set up Dolphin, you need to use the HD Audio mod to easily change the in-game music.
Unzip the HD Audio mod's folder and remember where you put the contents. Then go back to Dolphin, right-click on Super Paper Mario, and select "Start with Riivolution Patches". Dolphin will tell you to find an .xml file, so go to the HD Audio mod folder → Riivolution → SPMHDSound.xml. Choose "Enabled" from the dropdown menu, click "save as preset", give it a title of your choosing, and save this to your Dolphin games folder. 

## Now, you have to convert your music into a format the game understands. 
Super Paper Mario uses .brstm files for its music, and most computers don't recognize that file type. Thankfully, some people on the internet have made it easy for us to change normal music files to .brstm.

Go to [mu-wave BRSTM Maker](https://kazuki-4ys.github.io/web_apps/mu-wave/), click the big button in the center of the screen to upload your song, and optionally drag the top-right arrow around to trim the audio. If you're changing background music, make sure to check the "Loop?" checkbox and set the loop's starting point by dragging the top-left arrow. Once you're satisfied, download the .brstm file and give it a temporary name.

## Time to finally put your custom music into the game!
Use [Nikku BRSTM Player](https://kenrick95.github.io/nikku/) to play the .brstm files in the "SPMHDAudio" folder of the HD Audio mod. Once you find the song you want to replace, change your custom song's filename to the EXACT filename of the original song, move your custom song to the "SPMHDAudio" folder, and replace the original song! If you've done everything correctly, you should now be able to start the game through your custom-named game file in Dolphin and listen to your custom music! You can also easily play with the default music by starting the game without the Riivolution patch or changing the setting back to "Disabled". 
