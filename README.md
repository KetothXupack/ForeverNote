# ForeverNote

Open-source Evernote application for Linux, with ability to run on Windows & Mac

Uses Evernote Web, created with JavaFX

# NOTICE
Development of this version of ForeverNote has been suspended due to severe limitations and lack of support for JavaFX. [I recommend using Tusk instead](https://github.com/klaussinani/tusk)

## Current Version: 1.3

## New Release Notes
- Fixed clicking on notebooks on the left panel and creating new notebooks
- Added a feature to hide the search bar after performing a search
- Fixed opening URL's in the user's default browser
- Fixed viewing note history
- Added release notes
- Added option to contact developer (me)
- Added update notifications

## Known Issues
- Pasting is buggy

## Features
- Most of the functionality of official Windows & Mac Evernote desktop clients
- GUI similar to official clients
- Stays in tray upon closing
- Saves username for next login
- And more...

## Preview
![alt tag](https://github.com/milan102/ForeverNote/blob/master/preview/forevernote.gif)

![alt tag](https://github.com/milan102/ForeverNote/blob/master/preview/forevernote_sample1.png)
![alt tag](https://github.com/milan102/ForeverNote/blob/master/preview/forevernote_sample2.png)
![alt tag](https://github.com/milan102/ForeverNote/blob/master/preview/forevernote_sample3.png)

## Development
- Download the latest OpenJFX library for your platform here https://openjfx.io/
- Set-up the library as a dependency in your IDE
- Set the main class as ```forevernote.Main```
- In your IDE's VM options pass ```--module-path /full/path/to/your/javafx/lib/folder  --add-modules=javafx.controls,javafx.fxml,javafx.graphics,javafx.web,javafx.swing```
