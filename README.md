# DoubleXP-ChromieCraft

This is an addon for WoW 3.3.5 (WOTLK) on ChromieCraft private server.

Its purpose is to give time before the next double XP Weekend, or time left before the double XP Weekend ends.

It's standalone, that means it does not need any external library.

As WoW API for 3.3.5 doesn't give an accurate Server time, you need to manually adjust the offset of your timezone. It's not the real offset but the offset compared to server time. There's a slash command for that (/dxp offset <value>).

## Install

### Downloading ZIP file

1. On Github, download project as a ZIP file (either from `Releases` on the right or the green `Code` button at the top right - then `Download ZIP`).
2. Open the ZIP, open the "DoubleXP-master" folder, and place this next folder's content in the `Interface\AddOns\` folder of you WoW installation. You need to put the directory there, not the files. And there must only have one directory called DoubleXP-master.
3. (Optional) Rename the directory to `DoubleXP`

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

4. Activate the Addon either using the `Addons` button in the bottom left of the `Character Select` screen, or using `ACP`.
