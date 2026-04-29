---
layout: default
title: 2-Editing Audio
nav_order: 4
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
<img src="images/podcast-edit-01.png" style="float:right;width:180px;" alt="podcasting icon">
# Editing Audio in Audacity
Now that you have recorded some audio for your podcast, let’s do some editing! 

If you have any questions or get stuck as you work through this in-class exercise, please ask the instructor for assistance. Have fun!


1. Please either use the audio you recorded in [Activty #1 - Podcast Recording with Audacity](recording-audio.html), or Download this [sample podcast interview file](images/goat-girl.mp3){:target="_blank"}, and then proceed to step 2 below.
- Note: If you are using a Mac please follow these additional instructions for [Importing or exporting audio using FFmpeg instructions](https://support.audacityteam.org/basics/installing-ffmpeg){:target="_blank"}

## Deleting unwanted audio from a track

For now, don't worry about cutting out filler words, like _uhms_ and _ahs_. But, do pay attention to where loud or disruptive breath sounds occur between sentences. It can be easy to cut breaths in unnatural ways and cause a "hiccup" or double-breath effect. 

When trimming out breaths, be careful not to accidentally cut off the beginning of a word (words starting with soft beginnings—like "F", "H", "S"—are especially easy to accidentally cut). 

We will start by getting used to Audacity's editing features by trimming the first few seconds of your audio track. We are doing this so that there isn’t an uncomfortable pause at the beginning of your track. Then, we will do the same at the end of the track. 

<img src="images/podcast-edit-02.png" style="float:right;width:2400px;" alt="select tool, hover curser">

### Trimming the track start and end

- In Audacity, look in the main menu bar and click on the **Selection Tool** icon.
- In the Audio Track, hover your cursor over the very beginning of the audio track (to the farthest left, near the left "0.0" mark), then **click, hold, and drag to highlight** the part of the track you want to remove. audio before you began speaking. Whatever you have selected will turn the background lighter in colour.
- Press the **Delete** button on your keyboard to remove the audio.
- Do the same for the end of your audio recording, by **selecting the audio** you don’t want, press the **Delete** button on your keyboard.

    <button onclick="toggle('gif1')">Show / Hide Animation </button>
    <div id="gif1">
    <img src="images/podcast-edit-03-2024Oct.gif">
    </div>
- As you did for trimming the beginning and end of the track, you can select audio from anywhere middle of your audio track, and then press the **Delete** button on your keyboard.

### Inserting or copying audio into your audio track

This is helpful in situations where you might want to move the order of your content around. For example, you might want to change the order, later, of a quesiton and answer. 

- **Select** a few seconds of audio from the middle of your recorded audio, then, in the main menu, select **Edit -> Copy**. 
- Somewhere else in your audio track, where there is a gap in speaking, click on the timeline and then select **Edit -> Paste** to insert the copied clip.
- You can also copy voice, music, or background “silence" audio from another track and paste it into your main podcast interview audio track.

> NOTE: the locations of buttons in Audacity's interface vary from version to version and system to system (i.e., Windows, Mac, or Linux). If you do not find what you are looking for, rely on the main menu to copy/paste.  

<button onclick="toggle('gif2')">Show / Hide Animation </button>
<div id="gif2">
<img src="images/podcast-edit-04-2024Oct.gif">
</div>

<img src="images/podcast-edit-05.png" style="float:right;width:200px;" alt="track example">

### Adding fades and crossfades 

We add fades and crossfades to address abrupt starts and stops in speaking, which can sound unnatural. 

- Fade the beginning of your audio by **selecting the first 3 or 4 seconds audio** (on the far left of the track), and then on the top menu select **Effect -> Fade In**.
- Fade the end of your audio track by **selecting the last 3 or 4 seconds of audio** (on the far right of the track) and then on the top menu select **Effect -> Fade Out**.
- You can also apply these fade techniques to any music you add to your track, which we will learn about later.

<button onclick="toggle('gif3')">Show / Hide Animation </button>
<div id="gif3">
<img src="images/podcast-edit-06-2024Oct.gif">
</div>

<!-- <img src="images/podcast-edit-07.png" style="float:right;width:250px;" alt="noise reflection editing menu"> KSS note: I commented out this image link becasue this page does not address Noice reduction -->

### Exporting your audio in High MP3 quality

We still have more to do for a finished product, like adding music "bumpers" (transition or break music), or voiceovers. For now, let’s practice exporting our file in order to get used to the process. 

- Select on the top menu: **File -> Export Audio -> Export to Computer -> Format: MP3 Files** and then click the **Export** button.
- Edit the meta-data for your podcast (this is optional). Click OK.
- If you haven’t already installed the free library to export MP3 files you will be prompted to download a free copy of “**LAME**” that will do this for you by pressing the Download button. Follow the installation directions for your operating system (ask for help if you have any problems).<br>
- Audacity might ask you to install FFMPEG in order to export an mp3 file. See these instructions for details:

[Installing FFMPEG](ffmpeg.html){: .btn .btn-green }

Great Job!<br>

<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Editing Audio Transitions & Voiceovers](editing-audio-transitions-voiceovers.html){: .btn .btn-blue }

