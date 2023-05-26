# Changelog:
- 0.1.0: Beta Release

# SunVox Preset Bank Generator Mk2

This is an updated preset bank generator by Logickin, invited acheney to discuss about his patch card system and the suggestion for the former program, in order to provide an eco-system to maximize the current patch card and patch bank system in SunVox, so you can use acheney patach cards for storing any single mutable preset, or compress them into Logickin's highly compressed preset bank from the former c++ program for out of the box patch changing experience.

This Program can now be run using pixilang, which is a programming language made by the developer of SunVox, NightRadio. The reason to the choice of this lanauge is that it has the built-in SunVox library, so that the program can be updated effortlessly due to lack of external binding like java and rust, while it has covered every platforms, **EXCEPT for iOS**. Thus, users in the Warmplace (SunVox and pixilang) community can use the program everywhere, unless you have gotten yourself a fanzy iPhone or iPad (which I am using...).

# Guide:
1.  Create a sunvox project, placing the modules of your choice with different settings.
2.  Download pixilang, and open the pixilang program.
3.  Find and run the preset_bank_generator 2.0.0.pixicode in the pixilang program.
4.  Click the "Load" button, and use the file dialog to find your sunvox project.
5.  Once you have picked your file, you can further editing the file patch using the textbox adjacient to the load button.
6.  After you have confrimed your import path, give an export name using the text box below the input path.
7.  Choose the export options, you can export your synths as patch cards or patch banks.
8.  Once you have done all the step above, press the export button; the program shows a popup for you to make a confirmation.
9.  If you click OK, the conversion begins.
10. Once the program has finished, it shows a popup to notify user, so that user can get their presets in the export folder.