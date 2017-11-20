## Follow along at: [https://maptimela.github.io/python-bs4-qgis](https://maptimela.github.io/python-bs4-qgis)

# Objective
In this tutorial we will learn: 
* a bit about Python (very basic/brief introduction)
* a bit about BeautifulSoup
* a bit about QGIS

# What data will we use?
We are going to be using precipitation gage data from LA County. The first table will be relatively static (only changes if they add or remove gages). The second table is constantly updated rainfall for each gage.

# Scope
We are only going to be pulling data for a single gage, but with these tools you can expand your Python scripts to pull multiple gages.

# Advanced
If you finish early and want a challenge, update gage_rain.py to pull in multiple gages at once into the same csv. As long as you populate the id field from the url, you can use the same relation in QGIS.