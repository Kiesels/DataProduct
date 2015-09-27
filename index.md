---
title       : Reproducible Pitch Presentation for Developing Data Products
subtitle    : Calculation of the square of hypotenuse
author      : TT
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Reproducible Pitch Presentation

The presentation contanins 5 slides to pitch the idea has been done in Slidify.
The Pythagorean theorem states that the square of the hypotenuse (the side opposite the right angle) is equal to the sum of the squares of the other two sides
The theorem can be written as an equation relating the lengths of the sides a, b and c, often called the Pythagorean equation.

Source:
Wikipedia
https://en.wikipedia.org/wiki/Pythagorean_theorem

---

## Pythagorean theorem

The Pythagorean theorem states that the square of the hypotenuse (the side opposite the right angle) is equal to the sum of the squares of the other two sides
The theorem can be written as an equation relating the lengths of the sides a, b and c, often called the Pythagorean equation.
The square of hypotenuse c^2 will be calculated by formula:
                              "c^2 = a^2+b^2")

---

## How to use the application

In order to calculate square of hyptenuse (the side opposite the right angle in a triangle) the length of two other sides has to be determined.
The following variable has to be entered (value shouldn't exceed 100):
Lenght of leg#1 (a),
Lenght of leg#2 (b)

After pushing submit button the value of square of hyptenuse is shown.

---

## Calculation of square of hyptenuse


```r
# calculation fuctions
c2 <- function(a, b) a^2+b^2

# Calculation example of square of hyptenuse:
c2(3, 4)
```

```
## [1] 25
```

