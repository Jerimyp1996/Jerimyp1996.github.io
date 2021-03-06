---
layout: post
title: "My Video Game - Final Submission"
date: 2019-03-08
---

# Video Game Submission

Shared link to my game:

https://www.wescheme.org/view?publicId=KFHNREJoPl

# Game Title: 
  Robot Adventures

# Describe your game, characters and setting: 

  The Robot(you) is trying to find additional parts to his suit/body because he is slowly starting to rust. This is why there are screws in the game which I labeled as the Target. The robot is trying to collect the screws in order to repair himself. The danger is then the water because it increases the rust on him and inevitably destroys him. We all know that robots and water do not mix so this is why I decided to pick this as the Danger. The setting/Background is just a plain background that does not really correlate with the story.

# Part of my Video Game 

 update-player : Number String -> Number
 
 EXAMPLES:
 
(EXAMPLE( update-player 320 "up")  (+ 320 20))
(EXAMPLE( update-player 100 "up")  (+ 100 20))
(EXAMPLE( update-player 50 "down") (- 50  20))
(EXAMPLE( update-player 150 "down")(- 150 20))

 Definition:
(define(update-player y key)
  (cond
    [(string=? key "up")  (+ y 20)]
    [(string=? key "down")(- y 20)]
    [else                    y    ]))

# Describe your code above.
 update-player : Number String -> Number

--> This is the contract of the function, it acts like a note to the programmer as to what the function should include. In this case, the update-player function takes in a number and a string and then outputs a number.

 EXAMPLES:
(EXAMPLE( update-player 320 "up")   (+ 320 20))
(EXAMPLE( update-player 100 "up")   (+ 100 20))
(EXAMPLE( update-player 50  "down") (- 50  20))
(EXAMPLE( update-player 150 "down") (- 150 20))

--> These are the examples of the function, update-player. The first example shows the number as 320 and the string as “up”. What follows it is the racket code for it: (+ 320 20). All this shows is that the player is located at the y-coordinate “320” and then the up arrow key is pressed. I chose to make the distance is travels everytime the up or down is pressed, 20. So in this scenario it would start at 320, the up key is pressed, and it then moves to 340. Then, next line of code follows the same pattern with the up arrow key, but as for the next one, it is a little different. Instead of the up arrow key being pressed this shows an example of the down arrow key being pressed. If the y-coordinate is 50 then the next output would be 30 because of this racket code that follows: (- 50 20). The last example then shows a similar interaction but just with a different y value.

(define(update-player y key)
  (cond
    [(string=? key "up")  (+ y 20)]
    [(string=? key "down")(- y 20)]
    [else                    y    ]))

-->This is the definition of the update-player function. The variables are labeled “y” and “key”. The y represents any given y-coordinate of the player and the key represents the up or down key pressed. After the “cond” function is introduced here, it proposes three different conditions. The first one is when the up arrow key is pressed and this adds 20 to the given y-coordinate. The next condition is if the down key is pressed. When it is, it subtracts 20 from the y-coordinate. The “else”, then represents if another key is pressed, this just does nothing but return the same y-coordinate. 
Describe the role of the function in the video game program.
The role of the Update-player function in the video game is so that the player(the robot) can move in an upwards and downwards direction by pressing the up and down keys.

# Describe the role of the function in the video game program.

The role of the Update-player function in the video game is so that the player(the robot) can move in an upwards and downwards direction by pressing the up and down keys.


# Screenshot of My Game

![Robot Adventures](/images/Robot Adventures.png)



