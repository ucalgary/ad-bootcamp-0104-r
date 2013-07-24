---
layout: default
published: true
classes:
 - slide
data:
  x: 2000
  y: 5600

title: Frame
---
* [a data table](http://cran.r-project.org/doc/manuals/R-intro.html#Data-frames)

		> p = c(1.99, 2.99, 4.99)
		> c = c(51, 24, 36)
		> data.frame(p, c)
		     p  c
		1 1.99 51
		2 2.99 24
		3 4.99 36
		> df = data.frame(price=p, count=c)
		> rownames(df) = c("squash", "cucumber", "tomato")
		