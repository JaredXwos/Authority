# Game Description
There is a board and a deck.
The game is turned based, and has a currency called "Authority"
The board is a simple 19x19 square grid.
The players are represented by squares that can move around the board.
The player has three cards at all times. If a player has less than three cards, the player draws exactly enough cards to make three cards. The players do not draw cards for any other purpose.
There are only two kinds of cards. Quest cards and square cards.
Quest cards are cards which state a condition that needs to be fulfilled e.g. "Move 5 squares consecutively in a straight line". They also have an authority cost and an authority reward corresponding to the difficulty of the condition. Completing the quest gives players the authority reward.
Square cards are cards that state special conditions of a square, e.g. "This square cannot be entered". They also have an authority cost corresponding to the special condition.
Every turn has four phases. These include setting conditions, abusing authority, moving the piece, and collecting rewards.
When setting conditions, the player decides which of the three cards the player wants to use. When a quest card is used, they are added to the amount of active quests. When a square card is used, the player uses applies the conditions stated on the square card on any vacant square.
Players can abuse their authority on quests and squares. They can limit the people who are allowed to complete specific quests by paying the authority cost. Players are only allowed to limit, they cannot allow people access to these quests, only block them. In addition they can also choose to override squares, dispelling any special conditions on the square for all players, by paying the authority cost.
Players then move their own player square by one square horizontally or vertically but not diagonally. After this is done, they collect any authority rewards obtained by completing quests. Once a quest is completed it can no longer be completed. 
At the end of each turn the authority cost of quests increases by 1 for the player.
At the beginning of the game, each player selects a quest above a specific authority cost to be a "winning condition". If any players complete any of these winning conditions throughout the course of the game, they win the game. It is to be noted that you can abuse your authority even on winning conditions. As such you can also win on default if you're the only one with access to these win conditions and you can also lose on default if you lose access to all the win conditions.
Square cards can include: "Teleport upwards as many squares as possible to a maximum of three squares", "Gain 5 authority". Square cards might include: "Mandatory swap cards with another player", or other cancerous rules as see fit.
Quest cards can include: "Step on the 4 distinct squares 4 times", "Make contact with the centre square", "Move past y=9", "Make contact with 2 sides".
Cards that can be win conditions include: "Make contact with 4 corners", "Move 130 squares"
# Road Map
![RoadMap drawio](https://github.com/JaredXwos/Authority/assets/60027693/e9c544fc-6423-4a91-815f-c83d59da6758)
# UI
This is the UI thus far.
![Figma](https://github.com/JaredXwos/Authority/assets/60027693/14f714e8-4456-4c94-ad84-376d8f12b48f)
# Help me
Having more figma artists, game balancers, playtesters, and/or coders would be good.
