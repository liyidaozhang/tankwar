# Tank War

## Game world
**Tanks**: a total of two, each tank is divided into turret, tank cap, body and two tracks, when the tank stay in place is to issue the engine idling sound, when the tank is running when the engine running sound

**Game environment**: including ground, house, sky, and so on
**Camera**: responsible for tracking two tanks, always aimed at the midpoint of two tanks

**Game manager**: itself without renderer, only script, responsible for the background music playback and switching

## Game rules
There are two players to control the tank, one with the arrow keys control, tab key fire, a control with wsad, space bar fire, each firing range fixed, hit immediately after subtracting 10-20hp, when a tank of blood When 0, the tank explodes and plays the other side of the winning music