# Vs. Gradius Free Play Attract Mode

[![Check out a demo of this hack in action](https://img.youtube.com/vi/zy1CTAb-dAQ/hqdefault.jpg)](https://youtu.be/zy1CTAb-dAQ)

Features:  
- The game will go into attract mode while in free play, limiting potential for burn in, and making your cabinet look cooler while it's powered on but not in use
- Press 1p or 2p buttons to insert coins, then choose 1p or 2p game as normal
- Game will automatically zero out your coin counter so that when you end your game, it goes back into attract mode
    - To continue, just press 1p or 2p again on the continue screen to insert coins then continue as normal

Requirements:
- Vs. System cabinet
- A Gradius/Goonies compatible daughtercard (game requires a VRC mapper, the normal 6 EPROM slots aren't used by this game)
- A M27C512 EPROM and ROM programmer
    - I used a GQ-4X ROM programmer to burn my copy and I used an original Fujitsu MBM27C512-20 EPROM, as this is exactly what my authentic Vs. Gradius PRG ROM was burned to, but probably any 27C512 EPROM will suffice.

Known issues:
- The game doesn't properly respect the other coinage dip switch settings while this hack is in place. I probably could fix this but it isn't really a priority for me, as this hack is intended for enthusiasts who keep their games at home on free play
- The checksum subroutine on boot will report ROM 1: OUT, as it will detect that the PRG ROM does not match what's expected. This is purely a cosmetic issue, and the game will still boot up totally fine.
