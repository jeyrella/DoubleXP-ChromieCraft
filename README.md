# DoubleXP-ChromieCraft

This is an addon for WoW 3.3.5 (WotLK) on ChromieCraft private server.

Its purpose is to visually display the time remaining before the next double XP Weekend, or to when the double XP Weekend ends.

It's standalone, which means it does not need any external library.

<FONT COLOR="red"> **_IMPORTANT_**

As WoW API for 3.3.5 doesn't seem to give an accurate Server time, **you need to _manually adjust the offset of your timezone_**. This is your timezone difference compared to server time, which is UTC (GMT). There's a slash command for this (`/dxp offset <value>` ).

## Installation ##

### Downloading ZIP file

1. On Github, download project as a ZIP file (either from `Releases` on the right or the green `Code` button at the top right - then `Download ZIP`).
2. Extract the ZIP to the `Interface\AddOns\` folder of your WoW installation. You need to put the directory there, not the files.  You could alternatively extract the zip elswhere and just move the extracted folder instead.
3. (Optional) Rename the directory to `DoubleXP` (from DoubleXP-main or DoubleXP-release depending on which download button above you used)

In the end, the directory structure should looks like this:

```
WoW\
   |
   .- Interface\
       |
       .- AddOns\
           |
	   .- DoubleXP\
	       |
	       |- DoubleXP.lua
	       |- DoubleXP.toc
	       |- DoubleXP.xml
	       |- LICENSE.txt
	       .- README.md
```

4. Activate the Addon using either the `Addons` button in the bottom left of the `Character Select` screen, or via `ACP`.
5. Set your timezone offset to GMT/UTC by using the command /dxp offset <value>
