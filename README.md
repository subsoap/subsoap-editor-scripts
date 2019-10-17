# subsoap-editor-scripts
Editor scripts for Defold

## Install

https://github.com/subsoap/subsoap-editor-scripts/archive/master.zip


## editor-script-create-sound-component.editor_script

Adds a right click context menu for .wav and .ogg files to create a basic .sound file for them next to them in their directory. Multiple files can be selected at once!

## editor-script-play-sound.editor_script

Adds a right click context menu for .sound .wav and .ogg files to play them with ffplay. ffplay is a required dependency and must be added to your path.

Problems: files can sometimes be locked with Java when playing!?, you can't stop audio playing once it beings, you can't play multiple sounds at once, and must wait for previous sounds to finish, you can't set the audio level so make sure your system level is low enough
