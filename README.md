Process national OSM dataset

so for each OSM link we will estimate the number of lanes (approximately). I have some logic somewhere in python

Then for each OSM link we will create a buffer based on the number of lanes

We will fill each buffer with H3 indexes of level 13

The final product will be a database with only two columns. First will be OSM id and the other H3 index
