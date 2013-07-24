---
layout: default
published: true
classes:
 - slide
data:
  x: 2000
  y: 1600

title: "Numerics, integers"
---
		> x = 3.14
		> class(x)     # print the class name of x
		[1] "numeric"  # numer is essentially “double”

		> y = as.integer(3.14)
		> y
		[1] 3
		> class(y)
		[1] "integer"
		> is.integer(y)
		[1] TRUE