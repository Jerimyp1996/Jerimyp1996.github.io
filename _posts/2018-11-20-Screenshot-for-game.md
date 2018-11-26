---
layout: post
title: My Screenshot
date: 2018-11-20
---

![Screenshot for game](/images/Screenshot for game.png)

This is a screenshot of the game that I am creating. The game consists of a robot(you, the player) trying to get screws for his "body". The screws are the target and the water is the danger. You have to jump to collect the screws but then also try to avoid the water. It is basically the game "NinjaCat" but with a little twist.

# How the Screenshot was created

This Screenshot was created in "Wescheme" in the bootstrap starter file, "Defining Values". The file gave me an outline for the game. There was already a placeholder for the background, player, target and danger. What I had to do was find a png image(with a transparent background) for the danger, target and background. I decided that he player that was already given was suitable for my screenshot. After I found my images, I had to define them to the certain function they pertained to. For example, I defined the water png image to "DANGER". I would do this by adding the image url(in this case, the water png image) to the "bitmap/url" function so that it would appear as an image on wescheme. The code looked like this; ```(define DANGER (scale 1.2(bitmap/url "https://www.freepngimg.com/thumb/water/6-2-water-png-thumb.png")))```. I also used the scale function for most of these images as they appeared to big on the screenshot. I scaled them to be smaller so they looked right on the screenshot. Lastly, after all my images were defined, I positioned them and placd them on the background using the put-image function. The code looked like this; (define SCREENSHOT (put-image DANGER 850 175 (put-image TARGET 560 450 (put-image PLAYER 320 260 BACKGROUND)))). The numbers next to the DANGER, TARGET and PLAYER are the coordinates(positions) that I set them to.



      
      
