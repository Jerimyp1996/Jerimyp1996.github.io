---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of United Kingdom by Jerimy Perez

## Describe your program

I designed a Flag for the United Kingdom. I made the United Kingdom flag pretty geometrically accurate, eye pleasing and scalable. Therefore, I think that I deserve at proffesional for my effort on the Flag and the scaling part. The Flag does indeed resemble the United Kingdom Flag and if you change one number in the code, you can scale it to your liking; whether its half the size or twice the size. 

## Current output

* * *
![final-flagUK](/images/final-flagUK.png)
* * *

## Describe your process.

At first, I thought of my Flag as two layers. The white background and the shapes on top of it. This worked because all I had to do was create the shapes and then position them correctly so they resemble the United Kingdom Flag. This was working great with the cross and the right triangles, but when it came down to make the "left triangles" and the upside down traingles, there was a dilemma. I then figured out that I could use the function "triangle/sas" to create these shapes. This function allowed me to create 90 degree left triangles. I was so excited because it meant I could finish my Flag. There was then only one more problem in the creation of this Flag. It was the diagonal rectangles. The positioning and creation of the shapes were easy, but making it look sharp at the end was not. During this thought process, I thought about making samll white rectangles to cover the tip of the rectangle and make it look cut. This in fact worked, and I had Finished my United Kingdom Flag.


## Explain your code

* * *

```
(put-image (rectangle 600 60 "solid" "crimson") 300 150(put-image (rectangle 60 (/ WIDTH 2) "solid" "crimson") 300 150
```

* * *

 This code shows the cross in the middle of the United Kingdom Flag. I created two red rectangles and positioned them in the middle so that they intersect and create a cross. The first rectangle funcion created the horizontal rectangle. It has a widty of 600(the whole flag) and a hight of 60. The poitioning of this is at 300(in the middle of the flags width) and at 150(also in the middle, but of the height). The nect retcangle function also creates a rectangle but vertically. It has a witdth of 60 and a height of 300(which is half of the flags width). The positioning then makes it go into the middle.


## Program code

```
;Definitions for height and width
(define WIDTH 600)
(define HEIGHT 300)


;-Measurements: width(60 * 10) height(30 * 10)

;-Traingle 1(big)

;(right-triangle 190 90 "solid" "darkblue")

;-Triangle 2(small)
;(right-triangle 170 70 "solid" "darkblue")

;-Rectangles

;(rectangle 60 (/ WIDTH 2) "solid" "red")

;(rectangle 600 60 "solid" "red")

;-Triangle(big and "reflected")

;(rotate 270 (triangle/sas 190 90 90 "solid" "darkblue"))

;-Triangle(small and reflected)

;(triangle/sas 170 90 70 "solid" "darkblue")

;-Diagonal rectangle

;(rotate 335 (rectangle 300 20 "solid" "red"))

;-Small white rectangle(for cut red rectangle)

;(rectangle 50 16 "solid" "white")

;-Flag program

(put-image (rectangle 70 16 "solid" "white") 408 112(put-image (rectangle 50 16 "solid" "white") 220 111(put-image (rectangle 50 16 "solid" "white") 370 189(put-image (rectangle 50 16 "solid" "white") 179 189(put-image (rotate 25 (rectangle 300 20 "solid" "crimson")) 100 45(put-image  (rotate 25(rectangle 300 20 "solid" "crimson")) 490 255(put-image (rotate 337 (rectangle 300 20 "solid" "crimson")) 520 60 (put-image (rotate 336 (rectangle 300 20 "solid" "crimson")) 60 255(put-image (rotate 270 (triangle/sas 170 90 70 "solid" "darkblue")) 530 230(put-image (rotate 90 (triangle/sas 170 90 70 "solid" "darkblue")) 60 73 (put-image (rotate 90 (triangle/sas 190 90 90 "solid" "darkblue")) 440 255 (put-image(rotate 270 (triangle/sas 190 90 90 "solid" "darkblue")) 160 45 (put-image(rotate 180(right-triangle 170 70 "solid" "darkblue")) 530 73(put-image (right-triangle 170 70 "solid" "darkblue") 60 230(put-image(rotate 180(right-triangle 190 90 "solid" "darkblue")) 160 255(put-image (rectangle 600 60 "solid" "crimson") 300 150(put-image (rectangle 60 (/ WIDTH 2) "solid" "crimson") 300 150 (put-image(right-triangle 190 90 "solid" "darkblue") 440 45(rectangle WIDTH HEIGHT "solid" "white")))))))))))))))))))



;- Defined Flag(Scaled)
(define Size 1)

(put-image (rectangle (* Size 70) (* Size 16) "solid" "white") (* Size 408) (* Size 112) (put-image (rectangle (* Size 50) (* Size 16) "solid" "white") (* Size 220) (* Size 111) (put-image (rectangle (* Size 50) (* Size 16) "solid" "white") (* Size 370) (* Size 189)(put-image (rectangle (* Size 50) (* Size 16) "solid" "white") (* Size 179) (* Size 189) (put-image (rotate 25 (rectangle (* Size 300) (* Size 20) "solid" "crimson")) (* Size 100) (* Size 45) (put-image  (rotate 25(rectangle (* Size 300) (* Size 20) "solid" "crimson")) (* Size 490) (* Size 255)(put-image (rotate 337 (rectangle (* Size 300) (* Size 20) "solid" "crimson")) (* Size 520) (* Size 60) (put-image (rotate 336 (rectangle (* Size 300) (* Size 20) "solid" "crimson")) (* Size 60) (* Size 255) (put-image (rotate 270 (triangle/sas (* Size 170) 90 (* Size 70) "solid" "darkblue")) (* Size 530) (* Size 230)(put-image (rotate 90 (triangle/sas (* Size 170) 90 (* Size 70) "solid" "darkblue")) (* Size 60) (* Size 73) (put-image (rotate 90 (triangle/sas (* Size 190) 90 (* Size 90) "solid" "darkblue")) (* Size 440) (* Size 255) (put-image(rotate 270 (triangle/sas (* Size 190) 90 (* Size 90) "solid" "darkblue")) (* Size 160) (* Size 45) (put-image(rotate 180(right-triangle (* Size 170) (* Size 70) "solid" "darkblue")) (* Size 530) (* Size 73)(put-image (right-triangle (* Size 170) (* Size 70) "solid" "darkblue") (* Size 60) (* Size 230)(put-image(rotate 180(right-triangle (* Size 190) (* Size 90) "solid" "darkblue")) (* Size 160) (* Size 255)(put-image (rectangle (* Size 600) (* Size 60) "solid" "crimson") (* Size 300) (* Size 150)(put-image (rectangle (* Size 60) (* Size 300) "solid" "crimson") (* Size 300) (* Size 150) (put-image(right-triangle (* Size 190) (* Size 90) "solid" "darkblue") (* Size 440) (* Size 45)(rectangle (* Size 600) (* Size 300) "solid" "white")))))))))))))))))))
```
