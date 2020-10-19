# Questions

| **Question**                             | **Answer** |
|------------------------------------------|------------|
| Need help with project Idea              |      N      |
| Need help setting up a private team room |      Y      |
| Who is your presenter                    |      ?      |
| Project category                         |     OTC Scanning       |

# Site Map

- [Home](http://wesleycoffman.github.io/) 

## Overview

Here I will document original work, research, and exploits done to manipulate the old flash game 'Adventure Quest' solely for fun. All exploits documented pose no danger but to give special abilities in-game. It is my duty to document these before Flash is banished from browsers starting in December of 2020. And with Flash, an era of Internet history is also banished.

## Scope

These exploits involve packet replay attacks via Burp Suite Proxy and local file mapping of tampered .swf files via Charles Proxy. Both cause a manipulation of the gaming engine to allow for excessive and unusual abilities in game, nothing more, nothing less. These meathods can be combined via a fancy double proxy to allow for best results. Game -> Charles -> Burp -> Game. Further areas to explore are the breaking of the client side D.I.Y. encryption used by the game developers. Fun stuff!

## Premise

Among my friend circle, it is no secret that I occassionally enjoy writing simple bots for the game 'Runescape'. These bots are solely for personal use. Growing up playing the game, these bots allow me to revive the experience and play it in a different way. Another childhood passion of mine is my childhood game 'Adventure Quest'. This game, much like Runescape, is still under development. Adventure Quest, unlike Runescape however, still puts most of the game engine client side. The developers, I am sure, are aware of this. The community behind Adventure Quest simply don't seem to care, unlike the Runescape community. Where Runescape has long fought botting and other cheats in personal progression in game, Adventure Quest merely tacks a shame on you player tag and the cheater is free to continue along their merry way. The only repurcussion for getting caught cheating in Adventure Quest is that the cheater's leaderboard status is dismissed. Hardly a slap on the wrist in my book. This difference in attitude is interesting, it does not happen per chance alone. Runescape, being a much larger game which seeks primarily to make money, has a large cheater base that has created an interesting, albeit illegal, economy. Though out of the scope of this writeup, I will link an excellent video on how the illicit Runescape market (I know, I was surprised it was even a thing), has been a means of immense profit for the citizens of Venezuela (https://www.youtube.com/watch?v=Ga3PbrZj1d0). Crazy stuff. Adventure Quest, on the other hand, seems to only continue development as a passion project of the creators. As such, given the small playerbase and lack of monetary gain as motivation behind the game, Adventure Quest cheaters are not punished as there is no monetary gain for their endeavors anyways. As such, no illicit market as seen above even exists, and as such I feel comfortable publishing my findings.

### Note:

I am slowly but surely documenting my research here. Feel free to bookmark this page and stop by regularly. You might find something new added!
