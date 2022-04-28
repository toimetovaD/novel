# Visual novel game
---
## Simple story about guy who just wants well-paid job
--- 
# -Application functionality-
Works like classic novel: shows pictures (backgrounds, sprites of characters), outputs text
## main menu:
![Logo](https://sun2.beeline-kz.userapi.com/s/v1/if2/_vRnUah3ij9aeMyl5M5Xt9fLfCtQ3VHN1EdbsTQR98Piu_p_uwGnpRyCJrTww_-SaXMBtj2oCSypnA-CdGBI71eq.jpg?size=1792x1001&quality=96&type=album)
yeah

---
# How does it work?
This novel was created on Ren'Py engine, based on Python.

At the first, i just added files that i need- backgrounds, characters' sprites, sounds and few animations. After that coding has began.
##### an example:
```
#characters
define e = Character('Эрика', color="#DC143C")
define v = Character('Веньямин', color="#FFD700")
define i = Character('Айзек', color="#006400")
define l = Character('Ленор', color="#483D8B")
define me = Character('я', color="#BC8F8F")
define b = Character('Босс', color ="#FFFFFF")
```

All of the sprites and backgrouns were drawn by my own. 
##### characters' sprites
![Logo](https://sun9-87.userapi.com/s/v1/if2/4Ghx1OaCKm1zNs-SfvVhMSVNohF24spQt1GkDlEB57Om4RlzBVgbJYAyTzJYsW_yXWucAdTSK9rCYipdG8SeHxlU.jpg?size=1500x1080&quality=95&type=album)

There are plot ramifications in game. To create them i used *menu* to give to player oportunity of choosing answer and *call* or *jump* functions to move the plot of game.
##### an exaple:
```
menu:
        "Позвать Эрику":
            jump callerika

        "Убежать":
            jump runaway
```
# CONCLUSION
## This game is simple and it is just an experiment, but I hope you'll enjoy it anyway!
---
## Thanks for attetion!!

-----
### i worked really hard at this project so i really hope you'll like it
![image](https://www.meme-arsenal.com/memes/3dfa53fec8cd648be8b8f86dcc6ebf66.jpg)
