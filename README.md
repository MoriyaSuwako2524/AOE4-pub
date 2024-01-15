# AOE4-pub
A private test repository for AOE4 pub.

This work derivates from another Chinese author "虚缈". I'm still deveploping the framework and proposed to release test version in the next few weeks.

Current changes corresponding to the native tavern.
1. Change systems of squad cards greatly, the details remains editing.
2. Change the settings of the health of the player. I hope to use villagers to object the health. Currently it's designed that player will start with 15 villagers with each villager provides 1 health. The villager can be killed in the defense round(seen in 3.), Which means that if all villagers are killed, the player will lose. However, players are allowed to own centers(up to 3), each center will provide 5 villager per round. It's also significant that villager determines the food that players get on round start. player get the ceil number of the villager/5. Thus if players are not damaged, they will get (2+round) food on round start. However, if too much villagers are killed, players will faced the decrease of their income. 
3. Add defense round , after the battle round, the player who lost the round will be invaded by the former player who defeated him. both player will deploy their army again, which means the squads in the battle round will join with the squads in the defense round. Generally, this will result in a more powerful army of the invading player. But the defending player will have different defenses, including their home center, outpost and keep. Players will begin with a home center as defense( can held 15 villager inside), and other powerful defenses will be acquired by cards. I hope this framework will restrain players who upgrade their levels too fast as AOE4 has huge gap between ages.
4. Landmark systems. On start of gameplay, player will start with level 1 and dark age. With the developing of levels, players who upgrade their ages have to select landmark cards which bring very powerful abilities.
5. 
