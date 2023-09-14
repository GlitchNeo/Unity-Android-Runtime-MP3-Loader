I made this cuz i couldnt find any simple code to run mp3 file during runtime from android (10+) without using any sort of plugins or extensions
So its just simple Drag and Drop
Works with Unity 2019+

Settings to be done if not done... or else the script won't work properly
Edit - Project Settings - Player - Write Permission - Change it to "External(SDCard)"

The MP3FileScanner script scans for mp3 files on storage
Drop the MP3FileScanner.cs on an Empty Game Object
and Assign the Variables

As for AudioManager.cs it has the fucntion to load the mp3 file in next scene (Player.scene)

I added a Visualizer script for testing

One can use this script for anything... whether be create mp3 player or a rythm game or just a loader

The Only Scripts that are Important are MP3FileScanner.cs and AudioManager.cs
Both Scripts have some Basic Instruction to guide you