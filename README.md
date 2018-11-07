# darkestlight
Actual name is tbd. The idea is to have singleplayer and local/online multiplayer

## Gamemodes
### The Darkest Hour
The premise: You and your party(if multiplayer) have a total of one hour to complete as many rooms as possible
- The game is over when 50% or more of your party is dead.
- Will have a unique score algorithm
  - score is roomsCompleted * x + (timeTaken/60 minutes) * kills
  - x starts at 1 and adds .1 for every 10 rooms you complete
- Has half the amount of loot rooms
### Survive the Night
The premise: your goal is to survive until the timer runs out
- Game is over when either you and your party(if multiplayer) die or when the time runs out
- The time selection
  - 10 minutes
  - 20 minutes
  - 30 minutes
  - 1 hour
  - 2 hours
  - 4 hours (these two very long ones are more for streamers than your average play time/get together with friends)
  - 8 hours
- For games an hour or longer, an intermission will be given every 30 minutes and requires
- The horde comes in waves. 30 second loot phases every 5 waves for you to buff your stats
- Every 10 seconds the speed of the monsters increase by a factor of 1.1. your player moves at a speed of 1.5.
- Score Algorithm (timeSurvived/modeTime) 
### Eternal Night
The premise: beat as many rooms as you can
- Game is over when you and your party die.
- Score calculated by (1 + 0.05 * x) * y + 10 * y
  - x is the rooms cleared
  - y is number of kills
  - z is torches lit
### Fend off the night
THe premise: keep the beacons lit while fending off the horde
- Game is over when you and your party die, or all the beacons are destroyed
- Your score is your time
