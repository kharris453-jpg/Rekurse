# Rekurse

**A playable video-feedback instrument for the browser.**

Point a camera at its own screen and the picture folds back into itself, over and over. Rekurse runs that loop as a simulation on your graphics card. Every frame is fed back through the dials you set, music nudges the system from outside, and patterns grow that neither you nor the music planned.

It is one HTML file. Download it, open it in Chrome or Edge, and play. No install, no account, nothing sent anywhere.

![A Rekurse frame: a magenta and green star blooming out of the feedback loop](screenshots/rekurse-1.jpg)

## Play it

1. Download the Rekurse HTML file (for example `Rekurse-0.22.2.html`) from the [latest release](../../releases/latest).
2. Open it in **Chrome or Edge**. Firefox and Safari run it, but much more slowly, and video export needs Chrome or Edge.
3. Read the safety notice, then turn the dials. Start with the presets, then use the microphone, system audio or a music file to let sound into the loop.

## For everyone

- **Presets to start from.** Pick a pattern recipe such as Prism tunnel, Cathedral or Spiral well, then nudge the dials and watch it grow into something of your own.
- **It reacts to sound.** Turn on the microphone or system audio and the picture listens to whatever is playing.
- **Live wallpapers.** Export a wallpaper for [Lively](https://www.rocksdanister.com/lively/) on Windows or an HTML wallpaper app on Android. Choose a light picture-only version, or one with a compact live control panel.
- **Scenes and replay.** Save the looks you like and let Rekurse glide between them on its own.
- **Recipe codes.** Share a whole tuning as a short code, and paste in other people's.
- **Paint into it.** Draw light straight into the loop, or drop in a picture or a fractal and watch the loop digest it.
- **Comfort guardrails.** A luminance ceiling, a flash guard and band softening are on by default.

## For music makers

- **Render a whole song.** Load an audio file and Rekurse renders a video of the full track offline. Every frame is drawn at full quality with the sound in exact sync, however heavy the scene, so you get a finished music video straight out of the app.
- **Music as a perturbation.** A beat tracker and per-band analysis (bass, mid, high) push on the loop rather than drive it, so the picture answers the song instead of just flashing along to it.
- **Shape the response.** Reactivity, input sensitivity, band separation, beat cut and beat punch set how hard and where the music hits. Tap tempo locks it to a beat by hand.
- **Plates played by the music.** A Chladni plate can take three voices, one per band, so the spectrum itself draws the figures.
- **Record live.** Capture a performance as you play, with the audio.

## For tinkerers and the science-curious

- **Homeostasis.** A luminance ledger keeps account of the light in the loop and inhibits regions that are running away. The loop stays alive for hours instead of burning out to white or fading to black, and it keeps finding new balance points while you play. You can set how strong it is and what energy level it aims for.
- **Physics, not canned effects.** Two hidden feedback fields cross-feed into the view. Past frames sit inside a simulated sheet of air, water or glass, and older frames lie deeper in it, so they are bent, tinted and colour-split more while caustics play across the surface.
- **Excitable media.** Belousov–Zhabotinsky waves, reaction-diffusion and the nodal figures of a vibrating Chladni plate can grow inside the loop and seed it.
- **Energy in, energy out.** The dials are grouped the way the system works: what pumps energy into the loop, what drains it, what reshapes it, and what holds it in balance.
- **Endless range.** The recipe dials and switches alone allow more than 10<sup>125</sup> distinct setups, more than the number of atoms in the observable universe (about 10<sup>80</sup>). And because the loop carries its own history, even the same setup never plays out the same way twice.

## The controls

Every dial sits in one scrolling strip of panels, grouped by what it does to the loop: energy in, energy out, shape, the physical medium, sources, the excitable media and the guardrails.

![The Rekurse control strip: recipes, music response, memory and medium, sources and display](screenshots/controls-1.jpg)

![The Rekurse control strip: energy in and out, shape, Belousov-Zhabotinsky, Chladni plate and guardrails](screenshots/controls-2.jpg)

## Gallery

Stills from a video made with Rekurse.

<table>
<tr><td><img src="screenshots/rekurse-2.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-3.jpg" alt="Rekurse frame"></td></tr>
<tr><td><img src="screenshots/rekurse-4.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-5.jpg" alt="Rekurse frame"></td></tr>
<tr><td><img src="screenshots/rekurse-6.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-7.jpg" alt="Rekurse frame"></td></tr>
<tr><td><img src="screenshots/rekurse-8.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-9.jpg" alt="Rekurse frame"></td></tr>
<tr><td><img src="screenshots/rekurse-10.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-11.jpg" alt="Rekurse frame"></td></tr>
<tr><td><img src="screenshots/rekurse-12.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-13.jpg" alt="Rekurse frame"></td></tr>
<tr><td><img src="screenshots/rekurse-14.jpg" alt="Rekurse frame"></td><td><img src="screenshots/rekurse-15.jpg" alt="Rekurse frame"></td></tr>
</table>

## Safety

Rekurse makes bright, moving and sometimes flickering light. If you or anyone nearby is sensitive to flashing images, don't use it. Stop if you feel unwell. The comfort limits are on by default; turning them down makes stronger light.

## Credits

Created, designed and directed by Kristian. Code written with AI assistance (Claude by Anthropic, plus other models), shaped through many design sessions and playtests.

## Inspirations

**Dave Blair, [The Light Herder](https://www.thelightherder.com/).** An analog HD video-feedback kinetic sculpture built from cameras, monitors, video switchers and beam-splitter glass. Seeing it run in real time is what made me want a playable version of that loop. Rekurse is an independent project. It is not affiliated with or endorsed by Dave Blair, and it uses none of his footage, name or designs.

**The Windows Media Player 12 visualizations** (Microsoft, around 2010). Alchemy, Bars and Waves, Battery: the built-ins a generation of us grew up with. They planted the idea that music could perturb an image rather than just decorate it.

**The merger.** I wondered if the two could be one thing: a feedback loop that grows novel patterns out of music's influence on it. That question is Rekurse.

Rekurse is not affiliated with, sponsored by or endorsed by Microsoft. Windows Media Player is a trademark of Microsoft Corporation, named here only to credit an inspiration. Video feedback itself is an old technique with a long history among video artists.

## Terms

Rekurse is free to use. Videos, wallpapers and scenes you make with it are yours. Please don't redistribute modified copies or sell it. It is provided as is, without warranty, and its comfort settings are not medical advice.

The page embeds the DM Mono and Manrope typefaces under the SIL Open Font License 1.1.

Copyright (c) 2026 Kristian. All rights reserved. This repository holds the released app only; the source is not published.
