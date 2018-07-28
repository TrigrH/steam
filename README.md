1. Extract/copy the two folders:

	images
	skins

to your steam folder (default locations below): 

64bit: C:\Program Files (x86)\Steam\
32bit: C:\Program Files\Steam\

it may ask to merge the skins folder, allow it.

2. In steam go: View > Settings > Interface

Select the skin you wish Steam to use (requires Steam to restart)
	Pick one:
	Steam-BottomLeft
	Steam-TopLeft
	Steam-TopRight
	Steam-BottomRight (styling tweaks only)

Press ok then press Restart Steam.

DONE!

-by TrigrH (add me on steam if you need help)

Note: big picture mode and announcement buttons are intentionally hidden.


HOW TO RESTORE THE OLD FRIENDS LIST STYLE (RECOMENDED)


Easy mode (no auto startup):

Use the shortcut provided to open steam (move it to desktop or something).
In steam go: View > Settings > Interface
Untick "Run Steam when my computer starts"
Done!

Advanced mode (with auto startup):

In steam go: View > Settings > Interface

Untick "Run Steam when my computer starts"

Open Task Scheduler using the shortcut provided.

At the top press Action > Create task...

In the name box call it "admin steam on login"

Tick "Run with highest privileges"

On the Triggers tab press New...

Set "Begin the task:" to "At log on"

Press ok

On the Actions tab press New...

Press Browse...

Find your steam.exe (C:\Program Files (x86)\Steam\steam.exe) - default

In the "Add arguments (optional):" box put:

-nofriendsui

press ok

Untick everything you can on the Conditions tab

On the settings tab untick "Stop the task if it runs longer than:"

press ok

Done!

