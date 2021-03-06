QuickOut
==========

First Android Game
====================================================================
API and support library
Game Engine: Libgdx (http://libgdx.badlogicgames.com/)
Physics Engine: Box2D
Android Game Development Tutorials: http://www.kilobolt.com/unit-4-android-game-development.html
OpenSource under Apache License

====================================================================

Sample object theme: animals and balloons

Gameplay: Objects appear in the screen randomly each level. On the top of the screen, 
there is a copy of one of the objects onscreen that will appear and vanish. Your goal is to burst the matching objects until they disappear from the screen. Drag object out of the screen to change the goal immediately. Burst a number of objects to end the round.

Points will be scored based on how fast you burst them, the time left after the round ends, and the maximum combos you have achieved.

Balls will keep spawning until they reach a certain maximum number, after which all of them will disappear and player will lose points (or current number of balls bursted).

Burst objects that match what the top says to score points.
Points will be deducted if you burst the wrong object, or input the wrong action.
To make the game more challenging, there are different actions available.

Onscreen HUD:
1. Balls collected
2. Score
3. Time indicator
4. Combo gauge
5. Individual ball score

Action list:

0. Description  (action-name)
1. quick tap the object (pop)
2. long tap the object (squish)
3. drag object out of screen (drag)
4. double-tap the object (dpop)

Pattern matching challenge example :

1. tap red, blue, green in order
2. drag every other color except x color
3. stick balls together 

Combo Gauge:


Bonus object:

0. Item description (Item name)
1. x2 score for x seconds, 2 makes x3, 3 makes x4 (Golden Touch) 
2. slow change rate for x seconds, 2 makes 2 times slower, 3 makes 3 times slower (Take your time)
3. slow disappearance rate or any level-specific bounce effects (Nullifier)
4. change every object to current match for x seconds (Matchmaker)
5. explode all objects  (Detonator)
6. helper AI to help for every correct action you make, and there is another object to match, the AI helper will do the same to one object. (Cheater)
7. Fast moving balls (Frenzy)
8. Small balls (Minimizer)
9. Slow timer (Slow Time)
10. No points deduction (No Penalty)
11. sucks in stuff ! (Vacuum)
12. wild card (Wildcard)
13. extends time by x seconds (Need More Time)
14. more balls! (Populator)
15. click-to-spawn ball (Popper)

Round rules:
1. Combo enabled
2. 3-Bounce-gone
3. 3-Bounce-change-type
4. Gravity-enabled
5. Bomb Detonator (Drag or long-press or tap 50 times)
6. x2 points reduction
7. No boundary
8. Temporary greyscale
9. 3-sec bomb
10. instant bomb
11. frozen ball
12. Tilt-screen only
13. Special Ball 
14. Special Ball - Pick the most colored ball

Business model
1. Score sharing. Challenge players on social media.
2. Energy game play time.
3. Buy extra slot to hold special items (max 3)

JSON data type
1. Use it for your game configurations instead hard coding in a class. 
2. Use for mockup database 
3. Again instead hard coding object attributes (enemies, players) use JSON, it is much tidier, neat and flexible.



