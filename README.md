# Smashface Goodstrong's GShade Presets

Welcome to the official home of **Smashface Goodstrong's Final Fantasy XIV shader presets!**

This is the result of months of fine-tuning for all scenes while playing the game, to ensure that they look great everywhere. Creating a preset is one thing, but making it compatible with every area of the game is much more difficult! That's the level of care and attention that has gone into these presets.

They're also highly optimized for lightweight operation on most machines. As a long-time ReShader and programmer with graphics design experience, I know which effects are too heavy, and which filters can be combined into one effect to achieve the same result. Everything has therefore been optimized to give you the most "bang for your buck". I've also provided instructions for optimizing things further for very low-end machines, but most people can run these presets as-is with great performance even on older hardware!

Have fun! :-)


### Important:

**Please read the "[How to Install](#how-to-install)" section** of this guide, which provides a complete step-by-step guide for installing the presets and getting the best performance and graphical quality out of them!

For a demonstration of what the presets look like in action, **check out the "[Video Demos](#preset-video-demos-in-4k60)" section.**


## Table of Contents

- [Preset Descriptions](#preset-descriptions)
  - [Faithful Realism v2](#faithful-realism-v2)
  - [Animu Desu v2](#animu-desu-v2)
- [Preset Video Demos in 4K@60](#preset-video-demos-in-4k60)
  - [Wrath of the Titan](#wrath-of-the-titan)
  - [The Ul'dahn Envoy, Scene 3](#the-uldahn-envoy-scene-3)
  - [The Ul'dahn Envoy, Scene 8](#the-uldahn-envoy-scene-8)
  - [A Royal Reception, Scene 1](#a-royal-reception-scene-1)
- [How to Install](#how-to-install) **(Read This!)**
- [Performance Tuning](#performance-tuning)
- [Update History](#update-history)
- [Copyright](#copyright)


## Preset Descriptions

*(Navigation: [Table of Contents](#table-of-contents))*

### Faithful Realism v2

This is the univeral "set it and forget it" preset for everyone who likes the original artstyle of the game, but just wishes that it wasn't so washed-out and flat.

It aims for richer and more vibrant colors for enhanced realism, along with excellent shadows, improved sharpness/clarity, subtle depth of field and vignetting - all achieved using a low amount of filters, and staying very true to the game's artstyle.

It also ensures 100% game compatibility so that you *won't* fall victim to typical preset incompatibilities such as overbrightening (blown out skies/ground), or extreme darkness, or oversharpening, or excessive depth-of-field blur anywhere. You don't have to worry about any of that here.

Just enable the preset and enjoy a more beautiful Eorzea!


### Animu Desu v2

Have you ever wished that you were living inside an Animu? Well, animu'chya glad ya asked that question! Because we all know that you need the animu desu in your life. What's this preset? Animu.

Based on the same high-performance techniques as the "Faithful Realism" gameplay preset, but whereas that preset aims for realism and staying true to the game's artstyle, this time we're turning all the Animu knobs up to 11! The extra processing does mean that it has slightly higher requirements, but it's still very close to the great performance of the previous preset. Clearly, this preset delivers a lot of Animu for your graphics card buck!

This preset is finetuned for the optimal amount of Animu for all lightning conditions and environments, as well as all world rendering distances, to deliver great results regardless of whether you're at the beach or in a deep dungeon. Nearby objects and people have Thicc Animu outlines for the overall character, and softer outlines for fine details such as facial features and armor. Faraway objects have thinner and increasingly faded outlines, so that you get a beautiful "painted horizon" feeling.

Everything has been finetuned to avoid the very common "line-drawing overload/dark lines everywhere/excessive darkening" effect, to instead give you something that looks more intentional and graceful than typical celshaders.

A lot of people are fans of this preset, and after playing with this "anime" style for a while, you may find it hard to use any other presets.


## Preset Video Demos in 4K@60

*(Navigation: [Table of Contents](#table-of-contents))*

These videos demonstrate the presets in some early A Realm Reborn scenes (to avoid spoiling the expansion stories). It should give you a good idea of the different artstyles! I would highly recommend choosing 4K resolution when viewing, since YouTube's compression blurs all lower resolutions.

*Tip: If you want an easy way to flip between the videos for comparison, then I recommend opening all videos for a scene into separate browser tabs, and muting the audio in all except one of the tabs, and then flipping through them quickly with `Ctrl-Tab` while clicking the playback bar at the exact same spot to sync up the videos. Then simply flip through the tabs with `Ctrl-Tab` and `Ctrl-Shift-Tab` while they're playing, to see the direct differences.*


### Wrath of the Titan

- [No Shaders](https://www.youtube.com/watch?v=9eI94oL4vyQ)
- [Faithful Realism v2](https://www.youtube.com/watch?v=1bS-d685I4M)
- [Animu Desu v2](https://www.youtube.com/watch?v=YcztJRvxkjY)


### The Ul'dahn Envoy, Scene 3

- [No Shaders](https://www.youtube.com/watch?v=KI-3CAsd7_0)
- [Faithful Realism v2](https://www.youtube.com/watch?v=lv2x8Jy6yaI)
- [Animu Desu v2](https://www.youtube.com/watch?v=dO0JUG3F_FE)


### The Ul'dahn Envoy, Scene 8

- [No Shaders](https://www.youtube.com/watch?v=N-piz4mVUZY)
- [Faithful Realism v2](https://www.youtube.com/watch?v=m9m6lRSUq4M)
- [Animu Desu v2](https://www.youtube.com/watch?v=Xwgil9PeCNU)


### A Royal Reception, Scene 1

- [No Shaders](https://www.youtube.com/watch?v=ICj9HUn0MCI)
- [Faithful Realism v2](https://www.youtube.com/watch?v=GdMsbnDb2oA)
- [Animu Desu v2](https://www.youtube.com/watch?v=2NBo511QoOA)


## How to Install

*(Navigation: [Table of Contents](#table-of-contents))*

1. Install [GShade](https://gposers.com/gshade/).
2. Set all of the [required and recommended GShade settings](https://gposers.com/gshade/gshade-faq/#1621713285919-4bab8037-ddb6) in Final Fantasy XIV. For reference, in case the link becomes invalid, the same settings will be described in the next steps below. Failure to do these settings will lead to graphical issues in certain environments (such as underwater).
3. Choose **DirectX 11** in the Final Fantasy XIV launcher settings.
4. Open the game, and click on "Configuration" in the main menu.
5. Switch to the "Graphics Settings" tab.
6. Set **"General: Edge Smoothing (Anti-Aliasing)"** to **"FXAA".**
7. Set **"General: Transparent Lighting Quality"** to **"High".**
8. Disable the **"Effects: Naturally darken the edges of the screen (Limb Darkening)"** checkbox.
9. Set **"Effects: Water Refraction"** to **"Off".**
10. Disable the **"Cinematic Cutscenes: Depth of Field"** checkbox. Otherwise you'll get smeared/blurry graphics. My presets actually take care of re-adding much better looking depth of field, so don't worry.
11. Switch to the "Display Settings" tab.
12. Set the **"Full Screen Mode Gamma Correction"** to **"50"** (the default). Otherwise the game will be affecting the preset brightness which will break the balance between shadows and light.
13. Set the **"Character Lighting"** to **"20".** This subtly increases the brightness of characters in dark rooms, making them easier to see, while still remaining natural. All of my presets have been created with this setting in mind. Don't go higher than 20 though, since you'll risk "washed out" characters in daylight if you do that.
14. After you're done configuring the game, it's time to install these presets.
15. [Download the latest version of my presets](https://github.com/Bananaman/Smashface-Shaders/releases/download/v2022.01.12/Smashface-Shaders-2022.01.12.zip).
16. Extract the **"Smashface Goodstrong"** folder into your Final Fantasy XIV folder's `game\gshade-presets` folder. (By default, it's at `C:\Program Files (x86)\SquareEnix\FINAL FANTASY XIV - A Realm Reborn\game\gshade-presets`.)
17. Press **F2** ingame to open the GShade interface. I suggest reading the initial tutorial if you're new to ReShade/GShade.
18. If the GShade font size is too small for you, go into the "Settings" tab of GShade, and increase the "font size" values.
19. On the "Home" tab of GShade, you will have a preset navigator.
20. At the top of the GUI, there's a folder navigation bar. You can either click the "..." to directly select the "Smashface Goodstrong" preset folder, or you can use the main bar to navigate to it.
21. Select your desired preset from the list of files.
22. To improve your game performance, see the "Performance Tuning" section of this guide. Even people with powerful computers should do the first step of those instructions.
23. If you want an easy way to toggle the presets on/off to see the difference, you can go into the "Settings" tab of GShade and set up a "Shader Toggle Key" binding.
24. I hope you enjoy my presets and have lots of fun in Eorzea! :-)


## Performance Tuning

*(Navigation: [Table of Contents](#table-of-contents))*

1. Enable the **"Performance Mode"** checkbox at the bottom of the GShade GUI. This is extremely important, and will give you massive FPS boost without any difference in visual quality. Everyone should do this step, regardless of how powerful your computer is!
2. All of my presets are highly optimized, using an effective set of shaders without bloat, so most people won't have to do anything else. But people with very old computers may want to do some further tweaking.
4. We use the "PPFX SSDO" effect by default, which is fantastic at creating deep shadows but may be too heavy for older computers. Therefore, my presets also have the "qMXAO" effect high up in the list for easy access. If your computer can't keep up, you can try disabling "PPFX SSDO" and instead enabling "qMXAO". The shadows will look much simpler, though.
5. Another heavy effect is the "ADOF", which creates beautiful depth of field whenever a character is closely zoomed in (such as during cutscenes). You may want to turn that off for old computers, since it's a pretty heavy effect which usually isn't even noticeable until you're in closeups.
6. Other than that, there isn't much else you can do. You might want to disable "Filmic Sharpen" to save a few frames, since the sharpening effect is pretty subtle and may not be worth the performance for you.
7. With these tweaks, the presets should run very well on most computers. I have received confirmation that they run well even on weak laptops without having to tweak anything, so most people will only have to enable "Performance Mode" and nothing else.


## Update History

*(Navigation: [Table of Contents](#table-of-contents))*

### Animu Desu, Version 2:

**Improvedo Editionu!**

- SSDO: Reduced saturation of color bouncing, to avoid overly saturated halos around certain objects.
- SSDO: Fixed extreme wrinkles when faces are very zoomed in. Was caused by the shader treating very shallow polygon angles (such as the face polygons around the mouth and nose) as crevices. Solved by increasing the angle required for creating a darkened area.
- HDR: Improved the HDR range so that it better handles both day and night without being too dark or too bright. This is always a difficult balancing act, but this time the result is even better than before.
- EyeAdaption: Added a new filter which automatically raises or lowers the brightness depending on what the player is looking at, to emulate the way human eyes adapt to light. This was necessary because the game suffers from overly bright highlights in daylight, and overly dark corridors where there's barely any light. This filter balances the brightness in a way that no other filters can achieve, and it helps naturally smooth out the transitions between various amounts of environmental light.
- Lightroom/Technicolor2: Improved "comic coloration" method. It's way less saturated than the first version of the shader, but you quickly become used to it. It's now very faithful to the game's original colors, and it doesn't oversaturate reds or turn cobblestone/bricks into blue/green splotches anymore.
- Comic: Fixed vertical stripes/lines on the legs of some characters, which was caused by overzealous mesh edge/polygon outline settings.
- Comic: Fixed darkening of waters/horizon, by clamping the comic shader's start offset for the horizon outlines. This was caused by my insistence to use "Type 2" outlines, which are very harsh in some areas, but overall look way better than the boring "Type 1" (which mostly just darkens the scene instead of making it look hand-drawn). But "Type 2" has a tendency to make the horizon very dark. That has been entirely fixed now.
- FilmicSharpen: Improved the sharpening of very fine details without introducing pixel artifacts.

Known Issues in Animu Desu v2:

- WONTFIX: Furry creatures such as Moogles get very dark hair if you zoom the camera in too much. It's a result of the shadow shader and comic shader reacting to the thousands of little hairs on their bodies, which causes their bodies to darken. There is no way to fix this without destroying the shadows and comic effects everywhere else in the world, so it won't be fixed. It's not a big issue, since it only happens you're very zoomed in. It won't even be noticeable at typical camera distances.
- WONTFIX: When you open very bright windows such as the world map, it can confuse the "Eye Adaptation" filter to think that the scene is suddenly brighter, which can make it apply less brightening at night and therefore cause the nights to become pretty dark and hard to see. There's nothing I can do about that. Just close the bright ingame window or make it smaller so that it has less impact on the night scene.
- WONTFIX: Foggy scenes look a bit strange, due to the shadows and comic outlines rendering through the fog. There's unfortunately nothing I can do about this, since that's just how the shadow and outline effects work.


### Faithful Realism, Version 2:

**More faithful! More realism!**

- SSDO: Enhanced shadows around objects for more lifelike realism\[1\].
- SSDO: Fixed the stripes/lines on faces in extreme character closeups\[1\].
- SSDO: No more colored halos around very colorful objects\[1\].
- FilmicSharpen: Improved the sharpening of fine details\[1\].
- EyeAdaption: Added eye adaptation which intelligently auto-adjusts brightness based on the scene, so that your eyes adapt naturally to dark rooms/tunnels or extremely bright days\[1\].
- MultiLUT: Rebalanced towards even more natural colors and better handling of bright scenes (such as the sky or bright roads at day).
- Lightroom: Better scene depth and balance between light and shadows, by adjusting the curves towards a calmer and more natural contrast.

\[1\] Imported finetunings from Animu Desu v2.

Known Issues in Faithful Realism v2:

- WONTFIX: Foggy scenes look a bit strange, due to the shadows rendering through the fog. There's unfortunately nothing I can do about this, since that's just how the shadow effect works.


## Copyright

The shader names and settings are the work of Smashface Goodstrong, and their official website is here:

https://github.com/Bananaman/Smashface-Shaders/

Contact me first if you want to include any of my work in a shader pack, or if you want to create any derivative works. Please respect the fact that these presets represent months of my hard work and time, and are being provided for free to the FFXIV community. I don't expect anything in return, except that you respect my hard work and don't rip it off. Don't be evil. Thank you.

