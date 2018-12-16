---
layout: post
title: Flag Project-In Process
date: 2018-12-14
---

# 1) Program code

```Definitions for height and width of flag
(define WIDTH 600)
(define HEIGHT 300)


--Measurements of flag: width(60 * 10) height(30 * 10)

--Traingle 1(big)
;(right-triangle 190 90 "solid" "blue")

--Triangle 2(small)
;(right-triangle 170 70 "solid" "blue")

--Rectangles(to form cross)

;(rectangle 60 (/ HEIGHT) "solid" "red")

;(rectangle 600 60 "solid" "red")


--Flag program--

(put-image(rotate 180(right-triangle 170 70 "solid" "blue")) 530 73(put-image (right-triangle 170 70 "solid" "blue") 60 230(put-image(rotate 180(right-triangle 190 90 "solid" "blue")) 160 254(put-image (rectangle 600 60 "solid" "red") 300 150(put-image (rectangle 60 300 "solid" "red") 300 150 (put-image(right-triangle 190 90 "solid" "blue") 440 45(rectangle WIDTH HEIGHT "outline" "black")))))))
```

# 2) My Flag
[Flagv2](images/Flagv2.png)


# 3) Reflection on Progress

 So far, this is what my flag looks like. It still needs 2 small triangles, 2 big traingles and the diagonal rectangle that has a cut edge at the end. A challenge that I am facing relates to the traingles that I still need to add. They are a reflection of the traingles that I already have but I'm not sure how to make them. The rotation function only rotates cuonterclockwise(from my knowledge), so how would I make the other triangles? If there was a way to reflect a shape or rotate it clockwise, I would be able to make my remaining shapes. Another challenge is the rectangle that goes diagonally. I think I have the right idea of creating a rectangle and then rotating it to fit the flag, but how would I make the rectangle be cut at the end? Perhaps I could create a small white rectangle to cover the end, so that it looks like its cut. Other than that, those are the challenges that I am going through while creating this flag.
