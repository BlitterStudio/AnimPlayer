# AnimPlayer
A multiplatform Amiga Anim player with playlist support
(c) 2016-2018 Dimitris Panokostas

![Alt text](https://github.com/midwan/AnimPlayer/blob/master/AnimPlayer.png)

## Features:
- Can play the following Amiga ANIM format files: ANIM5, ANIM7, ANIM8(L) ANIM16, ANIM32, YAFA.
- Can play the following non-Amiga formats: FLIC (FLC)
- Has playlist support. You can add a sequence of Anims and view them in the order you want.
- Has quick resize options for: Original, Double size. Also able to freely resize manually of course.
- Drag and drop support, adds files to playlist.
- Runs on multiple platforms: AmigaOS3, AmigaOS4, AROS (x86), MorphOS, Linux (ARM, x86, PPC), MacOS, Win32.
Note: Although you can run it on AmigaOS3, a real Classic will be too slow for it. You will need something
faster than 060 and RTG to make use of it in real life (so either under emulation or a fancy FPGA accelerator).
However, since there are already various Anim players for the Classic which perform quite well, I don't see
this as a big problem.

## Future:
- Add support for audio in YAFA Anims (samples or MODs), maybe. :)
- Have a feature request? Please let me know!

## Requirements:
- The application was designed to be portable, no installation is necessary.
- On Amiga-like OS, it requires MUI (or Zune).

### HISTORY
--------
Version 2.2 (2018-11-09):
- Fixed bug where loading an Anim from File->Open also added an extra blank entry in the playlist
- Fixed bug which threw an error if loading an Anim, while another was open and was never played
- Now linked the required plugins to the executable, so no external files are needed anymore
- Compiled with Hollywood 7.1

Version 2.1 (2017-05-01):
- Added drag and drop support now that the updated Hollywood 7 supports it
- Compiled with the newer Hollywood 7

Version 2.0 beta (2016-07-17):
- Fixed bug when playing Anims from a playlist, where the application would try to finish an Anim playback which was already finished.
- Will now keep a resized window dimensions when playing through a playlist (so new anims will be scaled to the window dimensions automatically)
- Will now show the current Anim filename in the window title

Version 2.0 beta (2016-07-05):
- First release for beta-testers! Please report any bugs.
- Added keyboard shortcuts for the various menu options.
- Repositioned some menu options in their most logical locations.
- Fixed "DEBUG was enabled" in previous build.

Version 2.0 beta (2016-06-08):
- Fixed a bug while playing files in a sequence from a playlist.
