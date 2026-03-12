All of this has been vibe-coded with the free version of Claude for Stable Diffusion ReForge with python 3.10 to work on my machine. I barely know how to do 'pip install'. I can't help troubleshoot anything if you have issues. If you're having trouble, your best bet is to paste the code into into a new chat with your own free account with Claude and get it to fix it to work on your machine (it will probably help to tell it what version of python you have and which flavor of Stable Diffusion you're using while doing so). Again, I have absolutely no idea what I'm doing.

This image browser is modeled after Irfanview, optimized for sifting though thousands of generated images. Using this program has greatly increased my ability to actually engage with my generations and pick out the best ones.
The program keeps track of everything by adding prefixes to image names. A viewed but unrated image will get a "-" prefix as soon as it's opened by the program (You can use the green A:- button to toggle this feature off). This feature is intended to help keep track of everything you've at least looked at, and helps with clean up steps from other features.
The UI will change color based on rating for easier clarity while browsing following videogame loot colors. Images can be rated from 0 to 5, getting corresponding prefixes and colors:

0: zzz_trash (red)

1: = (white)

2: _ (green)

3: __ (blue)

4: ___ (purple)

5: ____ (orange)


Ratings can go beyond 5, continuing to add underscores to the title. This is intended to make higher rated images appear first when browsing through the folder in windows explorer.
Ratings can be assigned by using the rating toolbar, number buttons on keyboard, or mouse 4 and mouse 5 for better 1 handed rating.


The buttons on the main toolbar are as follows (there are also tooltips built in if you hover your mouse over a button for a second or two):

Open folder

Open current file in windows explorer

Move all files to another folder (subfolders are preserved)

Toggle fit to window

Zoom in

Zoom out

Open thumbnail browser (see below)

Delete all rating 0 (trash) files

Sort files by keywords into subfolders (searches through png metadata for keywords, then sorts your images into subfolders accordingly)

Jump to subfolder (includes jump to last rated image and jump to last viewed image within those subfolders as well)

Show PNG comment metadata

Toggle auto prefix '-'

Rate all '-' as 0 (trash)

Change sort order

Toggle flat mode (ignore subfolders for browsing order)

Settings menu

Then there's the info block, containing the image index within the folder, the image index within it's subfolder as well as the subfolder name, the image's resolution, and the image's rating.

Cycle rating toolbar (top, side, hidden)


Thumbnail Viewer
the thumbnail viewer is also very extensive, mirroring most of the main browser's functions. the main differences are that actions are applied to whatever thumbnail you've clicked on, and the auto prefix with '-' function is replaced with a button that can add or remove that prefix to all images in the folder instead.
