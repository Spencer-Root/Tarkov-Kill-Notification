# Tarkov-Kill-Notification

[Escape From Tarkov](https://en.wikipedia.org/wiki/Escape_from_Tarkov) is a realistic, survival, first person shooter computer game released by [Battlestate Games](https://www.escapefromtarkov.com/) in 2017. The game has been in closed beta to a relatively small audience since then but gained significant widespread recognition at the end of 2019 when it became [the most watched game](https://www.pcgamesn.com/escape-from-tarkov/top-twitch-game) due to a promotional partnership with the online streaming platform Twitch.

My first impression of Escape From Tarkov was that it took realism very seriously. Unlike many of the first person shooter games released in the latter half of the last decade, players are not provided with a Heads-Up Display, or [HUD](https://en.wikipedia.org/wiki/Head-up_display_(video_games)), to rely on for information. Many first person shooters communicate vital game information to the player such as health, ammunition counts, status effects, cardinal direction, and map information.

Many of the first person shooters, such as Call of Duty and the Halo series, are fast-paced and take place on small to medium sized maps with a balanced number of players. These games take a traditional approach to UI and provide players with substantial information such as a popup/[sound effect](https://www.youtube.com/watch?v=B6IO3NcN_S4) when the player gets a kill. 

Escape From Tarkov is a slower-paced game that takes place on larger maps with fewer other players and can therefore afford to communicate much less information through UI. The player has to check their ammunition count manually, they cannot easily see how much health they have remaining, and they receive no notification when they kill an opponent. This user-unfriendliness coupled with the relative infrequency of interactions with enemies leads to some very intense stand-offs where players must make split second decisions and face-down the consequences.

Enter, [NVIDIA Highlights](https://developer.nvidia.com/Highlights). NVIDIA Highlights is a screen recording service that automatically captures significant moments in your gameplay and saves the video clips as files in a directory on your hard drive. A video clip file is added to the directory, while you're playing, quickly after any significant event (like killing an opponent) occurs.

My Python script uses the os, time, and winsound modules to 1) Watch the NVIDIA Highlights directory 2) Flag when the directory's contents change 3) Play a short sound in response to the flag.

This script empowers me to make more-informed decisions while playing Escape From Tarkov by notifying me when I successfully kill an opponent. No more surprise-he-ain't-dead moments or waiting to heal until after I check to make sure I'm safe. This script allows me to play more confidently because I have more information about in-game scenarios than provided by the user interface.
