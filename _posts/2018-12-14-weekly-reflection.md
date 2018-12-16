---
layout: post
title: Flag Project-In Process
date: 2018-12-14
---

# 1) Program code
```
;Definitions for height and width
(define WIDTH 600)
(define HEIGHT 300)

--Measurements: width(60 * 10) height(30 * 10)

--Traingle 1(big)
;(right-triangle 190 90 "solid" "darkblue")

--Triangle 2(small)
;(right-triangle 170 70 "solid" "darkblue")

--Rectangles
;(rectangle 60 (/ WIDTH 2) "solid" "red")

;(rectangle 600 60 "solid" "red")

--Triangle(big and "reflected")
;(rotate 270 (triangle/sas 190 90 90 "solid" "darkblue"))

--Triangle(small and "reflected")
;(triangle/sas 170 90 70 "solid" "darkblue")

--Diagonal rectangle
;(rotate 335 (rectangle 300 20 "solid" "red"))

--Small white rectangle(for cut red rectangle)
;(rectangle 50 16 "solid" "white")

---Flag program---

(put-image (rectangle 70 16 "solid" "white") 408 112(put-image (rectangle 50 16 "solid" "white") 220 111(put-image (rectangle 50 16 "solid" "white") 370 189(put-image (rectangle 50 16 "solid" "white") 179 189(put-image (rotate 25 (rectangle 300 20 "solid" "red")) 100 45(put-image  (rotate 25(rectangle 300 20 "solid" "red")) 490 255(put-image (rotate 337 (rectangle 300 20 "solid" "red")) 520 60 (put-image (rotate 336 (rectangle 300 20 "solid" "red")) 60 254(put-image (rotate 270 (triangle/sas 170 90 70 "solid" "darkblue")) 530 230(put-image (rotate 90 (triangle/sas 170 90 70 "solid" "darkblue")) 60 73 (put-image (rotate 90 (triangle/sas 190 90 90 "solid" "darkblue")) 440 254 (put-image(rotate 270 (triangle/sas 190 90 90 "solid" "darkblue")) 160 45 (put-image(rotate 180(right-triangle 170 70 "solid" "darkblue")) 530 73(put-image (right-triangle 170 70 "solid" "darkblue") 60 230(put-image(rotate 180(right-triangle 190 90 "solid" "darkblue")) 160 254(put-image (rectangle 600 60 "solid" "red") 300 150(put-image (rectangle 60 (/ WIDTH 2) "solid" "red") 300 150 (put-image(right-triangle 190 90 "solid" "darkblue") 440 45(rectangle WIDTH HEIGHT "outline" "black")))))))))))))))))))
```
# 2) My Flag
[flagV2](/images/flagV2.png)

[flag](/images/flag.png)


# 3) Reflection on Progress

 This is my United Kingdom Flag that was created using wescheme. There were two major challenges that I faced while creating this flag. One of them was creating the reflected triangles(left-angle triangles). They are a reflection of the right triangles that I already had but and I wasn't sure how to create them. I was confused because the rotation function only rotates cuonterclockwise, so how would I make the other triangles? I ended up using the "triangle/sas" function which allowed me to create the "left-triangles". SAS stands for side, angle, side, so all I had to do was put in those measurements and then rotate accordingly. Another challenge was the rectangle that goes diagonally. I ended up making a rectangle and then rotating it so that it fit the flag. After that, I created a small white triangle to put over the end of the red rectangle so that it appears to be cut. I did the same for all red diagonal rectangles, making my Flag complete. Other than that, those were the challenges that I went through while creating this flag.
