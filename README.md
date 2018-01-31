# MGQParadox-trn
Part machine, part human, but all complete translation of MGQ Paradox parts 1 and 2

### Notes
- As the description indicates, the majority of the translation is done by a *machine*. Some of the text may be silly, but it's enough that you can understand what's going on. Want it to be better? Take a look at "How to Contribute"

### Instructions
1. Download a zip file of the repository (big green button, upper right repository window)
2. Extract to anywhere with enough disk space for the game
3. Run 'Ytinasni.RpgMaker.GameSelector.exe' and select the folder that contains your copy of (untranslated) MGQ Paradox Parts 1 and 2
4. Copy all the files in 'main' into 'Scripts', overwriting everything in the process
5. Run 'Ytinasni.RpgMaker.Translator.exe', which will drop the game into the newly created 'out' directory
6. Go into 'out', run the game, and enjoy!

### For the nerds
- 'legacy' contains the first pass of my translations, merged with Dargoth's work (major props). This is what I compare to when something new doesn't work
- 'text' contains the intermediate output of the auto-translation program ("non-english" -> "english")- this is what the program patches into 'alpha', after which some manual cleanup follows before merging into 'main'. Edit this if you're looking to contribute
- 'alpha' the raw output of the translation progrom after loading the files in the 'text' directory

### How to Contribute
- Head into 'alpha' and take a look at any of the files- they contain Japanese phrases and their English counterparts in an easy-to-read format. See something silly? Edit the English part and send in a pull request for extra good karma
- If you're able, some of the main resource files (notably 