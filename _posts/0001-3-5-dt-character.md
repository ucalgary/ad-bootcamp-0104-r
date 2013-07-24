---
layout: default
published: true
classes:
 - slide
data:
  x: 2000
  y: 3200

title: "Character"
---
		> n = 'Nancy'
		> x = as.character(3.14)
		> class(x)
		[1] "character"
		> paste(n, x)      # combine strings
		[1] "Nancy 3.14"
		> sprintf("%s has %d dollars", n, as.double(x))
		[1] "Nancy has 3.14 dollars"
		