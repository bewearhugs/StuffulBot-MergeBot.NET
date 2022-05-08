![Stufful](https://cdn.discordapp.com/attachments/733453918498979944/964983965452738620/stufful.gif)
# StuffulBot Merge is a Gen 7/8 Sysbot for Nintendo Switch

**LGPE Sysbot done by SantaCrab420 - Merged by bewearhugs**

* [SantaCrab's discord](https://www.piplup.net)
* [Bewearhug's discord](https://tiny.cc/bwhd)

## About
StuffulBot Merge is a Generation 7/8 Sysbot for LGPE, SWSH, BDSP, LA Pokémon Games

## Credits
* PKHeX Crew etc. for Sysbot.NET
* Santacrab for getting LGPE working
* Friends who helped steer me in the right directions ;)

## Requirements
* -[Hacked switch with CFW](https://nh-server.github.io/switch-guide/user_guide/getting_started/)
* -[SysBot Base](https://github.com/olliz0r/sys-botbase)
* -[ldn_mitm](https://github.com/spacemeowx2/ldn_mitm) *if using SWSH*

## Game Mode Changer + Pictocode Embed (NEW!!!)
![GameMode](https://media.discordapp.net/attachments/861058349621444648/967503425543745566/unknown.png)
![FormPreview](https://media.discordapp.net/attachments/861058349621444648/967508653487849472/unknown.png)
* Select No to Boot, Select yes to restart - only restart if you changed the selection in dropdown menu for game mode change!

![pictoocde](https://media.discordapp.net/attachments/861058349621444648/968384357821722634/reeee.png)
- Now with a pretty embed ooohhhh ahhhhhh
- Pictocode quality improved and edges trimmed... so pretty!

## 6A Helper Module (Owner usage only)
* AnnounceHere / AH / ah - adds the channel the command is used in to the channel announce/changer list
* Announce / A / a - sends an embedded announcement for provided string message to all linked channels (use "" to wrap multiple words into one 'string')
* Change / CH / ch - changes the name of all the linked channels in announcelist to match provided string (use "" to wrap multiple words into one 'string')
* Off / off - changes the name of all the linked channels in announcelist to $"{bot.username} offline❌"
* On / on - changes the name of all the linked channels in announcelist to $"{bot.username} 'providedstring'✅"
* Yeet / yeet - leaves the server the command is executed in

examples:
&Announce "Bot is taking a break for a bit"
&Change "Bot Channel Name Example"
&Off (All linked channels will be renamed to = {bot.username} offline❌)
&On lgpe (All linked channels will be renamed to = {bot.username} lgpe✅)

## How to Run
1. Boot your Switch (assuming you are in Sys CFW mode)
2. Start the game of your choice
3. Edit your config for game mode and reboot exe if neccessary...  Mode:  0=LGPE 1=SWSH 2=BDSP 3=LA
5. Edit Hub, Add Bot, and hit Start All

## How to build
Download source code or git clone, open in VS, open Sysbot solution. Select Sysbot.Winforms as startup project and hit build (*x64 and Release*).

## Additional thanks
Thanks to everyone from PKHeX for their amazing library, and Archit and everyone for ALM plugin!
