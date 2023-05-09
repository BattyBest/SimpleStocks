# SimpleStocks
Stock Trading Simulator too accurate for its own gameplay sake

# What you need
A Ti-84+ CE
A transfer program capable of transferring ti-programs (TILP for Linux and Ti Connect CE for Windows and Mac are good candidates)
These files

Simply transfer the program and open it from the prgm key. That is it. SSTOCK is written entirely in TI-BASIC and is designed to work at first launch.

# Modding

Modding is done through the calculators L1, and code will go there. The ""program"" STOCKEV can be edited in the calculators TI-BASIC editor for instructions on how.
Included also in the github is NUMTEXT which allows you to type an arbitrary string and have it be converted into...numtext, which you can then use in your mod.
In the game itself, goto mods, it will detect any in L1, and allow you to either activate it, or disable it (and also disable any currently active mod), you can only have 1 mod active, maybe will change in the future.
It will need to "compile", which will do voodoo magic with the numtext and turn it back into a form readable by SSTOCK
Afterwards, the mod will be "active" for as long as the list STOCA and the string STR6 are not deleted, if either are deleted, re-enable the mod in SSTOCK.

# FAQ

Q: Can I contribute?
A: Of course, make a fork and then a pull request. I'll get to it. Eventually.

Q: Can I suggest a feature?
A: Make the feature and then a PR, I will maybe come up with a more convenient way.

Q: This seems very unproffesional...
A: Yes, it is a side project, I made it open source so that anyone can play it

Q: What does the slogan mean?
A: The best strategy in the game is to just buy a bunch of stocks and go into hibernation. Not fun, but realistic.

Q: Is there a more convenient way to make a mod?
A: "stat" and then "SetUpEditor" L1, then "stat" "Edit..." will open a editor thats more convenient than just augment and L#(#). A tree-like editor is also planned.

Q: I added a lot of events in a mod and it crashed in next turn!
A: Bug, currently if the screen fills up it crashes.
