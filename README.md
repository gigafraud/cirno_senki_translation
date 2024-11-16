# Cirno Senki Dialogue Translation

Here are the files containing the dialogues from Cirno Senki I've already put in the game.
I can still edit them in the future, if I see the need to do so.

--------------------------------------------------------


## How a file looks like

A line that starts with ;; is a comment, meaning it isn't executed. It allows to give information to the people reading the file.

You can see every file as a program that tells the game what to do. Like a program, it uses functions. Here are the main functions you'll see :




### *SLP length
EXAMPLE : *SLP 30

SLP is akin to a sleep() function. It means that the game pauses for a certain amount of time. The value is not in seconds, but I'm pretty sure it isn't in milliseconds either. I need to test it.




### *RED path/to/file
EXAMPLE : *RED チルノdata_stages/chirno_stage1/stage1_ENEMY4

This function simply executes another file. Usually, it will execute a stageX_ENEMYy file, which contains ennemies to spawn.



### *LHT characterName emotion
EXAMPLE : *LHT ミスティア 驚
           Eh ? Wait, what is this !?

This will put a character sprite on the left side of the screen with a specific emotion. If there's text on the line right under, it will show a dialogue box with the character's name, and show the dialogue.

*RHT does the same thing, it just puts the character sprite on the right instead.



### SND musicName
EXAMPLE : *SND BGM24

Plays a background music. As simple as that.


--------------------------------------------------------
There are other functions in these files, but I need to check what they actually do to be able to explain it.















