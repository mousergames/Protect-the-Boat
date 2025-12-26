# Protect-the-Boat
Protect the Boat will be a simple yet intense fighting game. The player will be tasked with protecting a boat from incoming pirates. It will be a wave based fighting game with complex swipe-fighting mechanics.

## Movement Mechanics
The only control in the entire game is swiping, no buttons or touchpads. If the player wants to move, the player will swipe in the direction in which they want to move, the magnitude (length) of this swipe will correspond to the force in which the player is moved in that direction. This creates a sort of jumping around mechanic where the player is highly mobile on the map. The player will only be moved in that direction once the player stops swipping.

#### Movement Mechanics Pseudocode
Initalize touch input variable
Initalize touch input transform

Update loop
set touch input variable to the first touch (Input.GetTouch(0))
set touch input transform to the position of the first touch
  


## Fighting Mechanics
With the swiping control, the movement doubles as a dash/attack. So, if there is an enemy to the right of the player and the player dashes in that direction, the player can dash through the enemy dealing damage. The damage is then amplified based on the force in which the player dashed through the enemy (magnitude calculation). In addition to dashing, the player will have a set of moves they can perform which are activated by certain swipe patterns. For example, if the player swipes in a cirle around themself the character will do a spin move dealing damage to all surrounding enemies. There will also be combination attacks, for example, if the player wants to spin while dashing, they can stack these attacks on top of each other. This means they could draw a circle around themself, then draw a circle to the left and the player would then be spinning and dashing to the left dealing immense damage to not just enemies the player passes through, but additionally enemies that surround the player in that direction. When an enemy is killed the player will gain coins as well as points, the coins and points given correspond to the type of enemy that was killed; bosses give more coins and points than basic pirates.

#### Fighting Mechanics Pseudocode

## Wave Mechanics
Waves will come with perdictable numbers of enemies. Meaning the first wave will have perhaps 4 enemies over a period of time, and then the next wave will have x1.5 of that so 6. When the wave number is divisable by 10 a boss will spawn in that wave. 

#### Wave Mechanics Pseudocode

## Buy Period
Between waves there will be a period where the player will be faced with a shop where they can use the coins they earned that wave or have saved from past waves to buy new weapons that deal more damage, or to heal themself, or spawn in fellow crew members that can help you fight, etc.

#### Buy Period Pseudocode

## Death
The player can die in two ways, either succumbing to their injuries from fighting the pirates or dashing off the side of the ship into the ocean. When the player dies, the game will essentially reset. Only a highscore remaining in the logs. 

#### Death Pseudocode

## Scoring
The player earns points through killing enemies and completing waves. 

#### Scoring Pseudocode
