---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Pakistan_ by _Jhon Paulino_

## Describe your program
The base of my program is ```(rectangle width height "solid" "dark green")```the rectangle is the shape of the base in other words a function. a rectangle function needs 2 numbers and 2 strings so i chose 500 and 300 for the length and width of my base as for strings i chose "solid" and "dark green" because it's the color of the background. the reason why there isn't any numbers in that contract is because i defined the numbers and substituted them for width and height.
## Current output

* * *
![Flag](/images/epicpakistanflag.png)
* * *

## Describe your process.
in the past week of working ive asked many questions that contributed to my final piece. The question that had the most impact on my project was asking how to rotate a star. When i got the answer i was confused but after working with my partner johnathen HE figured it out and taught me.


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
(put-image( rectangle bar width "solid" "white")
                                        rectangle-radius last-coordinate _
```

* * *

-   
 
so the funnction put'image is used to put one image onto the other, and since its a function it must start of with a opening parenthesis.then i add another function which would be the simple shape rectangle. A rectangle FUNCTION includes 4  arguements 2 vaulues and 2 strings. my 2 values were defined and translated into words hence the bar and width. my 2 strings are solid and white becaue they have the quotations, and to close the function with a closing parenthesis. since the put imagae function needs the coordinates a x and a y value were chosen you could not see this values because they were also defined by defining all my values all you have to do is change 1 number and the size of the flag will change.


## Program code

```
(define size 100)
(define width (* size 5))
(define height (* size 3))
(define bar(* size 1))
(define circle-radius (* 1/4 height))
(define star-radius(* .05 width))
(define radius(* size 1.75))
(define star-width(* size 3.2))
(define rectangle-radius(* 1/2 size))
(define radius-width(* size 3.15))
(define circle-height(* size 1.75))
(define circle-coordinate(* size 1.60))
(define last-coordinate(* size .55))
(define flag(put-image(rotate 18( star star-radius "solid" "white") )
          star-width radius
          (put-image(circle circle-radius "solid" "dark green")
                    radius-width circle-height
                    (put-image(circle circle-radius "solid" "white") 
                              height circle-coordinate
                              (put-image( rectangle bar width "solid" "white")
                                        rectangle-radius last-coordinate 
                                        (rectangle width height "solid" "dark green"))))))
```
