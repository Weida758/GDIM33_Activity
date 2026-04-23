# GDIM 33 In-Class Activities
## W1
### Activity 1
[Game Board](https://docs.google.com/drawings/d/16PMT3G0rWSyuW1FYPxnOVWyFQ4qM47eBJ2u_sxAnCQ0/edit?usp=sharing)

1. I found out that I really like fantasy games with unique combats or RPG elements that provides a good sense of strength progression. I also really like difficult games such as the Dark Souls series, Elden Ring, various metroidvania games, etc.
2. One of our table mate said that they really like colorful games with a bit of challenge in the aspects of puzzles built into the game. She also mentioned that the games she enjoys are mostly multiplayer coop games. I think our styles are similar in the way that her games are also very fantasy focused. Her idea of challenge being a core part of what makes a game fun is aligned with what I believe too as I enjoy difficult games.
3. The LA that talked to me talked about how he enjoyed roguelike/roguelite games. These games typically are heavily focused on the sense of becoming stronger, which is similar to how I want progression in my game. 


### Activity 2
Vampire Survivor Like game breakdown
<img width="1628" height="1171" alt="image" src="https://github.com/user-attachments/assets/1d79b31a-2602-4395-875e-aed7458cf8a7" />


## W3
### Activity 1
<img width="1633" height="758" alt="GDIM 33 Game Breakdown" src="https://github.com/user-attachments/assets/73dd3272-8c05-4040-9223-88aaf1ced1a8" />


### Activity 2
  1. Saving the string for the event name as a scene variable is beneficial because you only have to edit the variable to apply changes to all nodes that utilize the variable. Aside from that, it also prevents errors by avoiding the case where you typed out the string differently at one node.
  2. Using Debug.Log at the custom event helped me notice that the event isn't being triggered and something is wrong with my Walrus graph is trying to trigger the event in the Walrus game object, while the event was defined in the GameController.
  3. Yes because we want our cursor to be shown for the UI menus to show where we are clicking and disappear when we are playing the game.
  4. Yes because my vampire survivor game can have a leveling up state where the game is paused while the player selects upgrades. 


## W4
### Activity 1
- In my current build, the player is able to in top down left right directions in a top down 2D environment. The player auto attacks in a radius centered at the player's body which reduces the health of enemies that are inside of that radius when the attacks happens. Enemies spawn around the player in waves separated by time intervals.
- My playtesting goals is to see how the basic mechanics currently feel right now and to see if there are any bugs in the game.
#### Playtesting Notes: Group is Weida Chen, Leandro, Gael Parras, Andrew Hsur, Lillian Su
- Players wasn't sure what was supposed to be going on at first because the first wave of enemy doesn't spawn immediately.
- Players wasn't sure where the attack is since there is no visual for the attack yet.
- Enemies can spawn outside the border.
- Everything else seems ok

### Activity 2
1. A writer would be able to add more dialogues without adding onto the code, because they can just create more DialogueLine scriptable objects and use that as dialogue lines with or without replies to form a continuous conversation by filling out the SerializedFields of the scriptable object that corresponds to the string of the dialogue line, and the reply nodes that comes after the line.
2. Technically, there is no limit, but practically, creating the dialogues manually becomes too messy by managing scriptable objects for a game that has thousands of lines of dialogues or more, since you'll have to create a scriptable object for every single line and reply.
3. Regenerating Nodes basically just have Unity scan the project again and register any custom class that doesn't inherit from Unity defined classes for visual scripting purposes. 

