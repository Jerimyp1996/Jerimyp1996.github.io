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

[flagV2](/images/flagV2.png)


# 3) Reflection on Progress

 So far, this is what my flag looks like. It still needs 2 small triangles and 2 big traingles
