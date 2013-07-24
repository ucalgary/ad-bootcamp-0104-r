---
layout: default
published: true
classes:
 - slide
data:
  x: 3000
  y: 800

title: "Load Data"
---
* CSV
		> pt = read.csv('Parking_Tags_Data_2012-10000.csv')
* Microsoft Excel
		> install.packages()    # install the gdata package if needed
		> library(gdata)
		> pt = read.xls('Parking_Tags_Data_2012-10000.xls')
* use head() to peek at the first few rows of a data frame
