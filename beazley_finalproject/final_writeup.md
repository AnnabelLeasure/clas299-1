# Amphora and Krater Distribution Patterns
### Original Research by Natalie DiMattia and Annabel Leasure

Using data from the Beazley Archive hosted at the University of Oxford’s Classical Art Research Centre, this project aimed to explore possible connections between the variations in amphora and krater shapes and the distribution of their find spots.

The Beazley Archive is the world’s largest collection of photographs and information on ancient Greek painted pottery and contains 117,751 entries (“The Beazley Archive.”). Using a Jupyter notebook, that data was narrowed down to the 47,551 pieces that had information regarding the pottery’s shape name, provenance, date, latitude, and longitude. From that cleaned up data set, we then extracted the amphora entries and the krater entries. We then mapped the data using QGIS software. The Jupyter notebook used and the original data set (in a tsv file) are available in a github repository [here](https://github.com/nadimattia/clas299/tree/master/beazley_finalproject).

**AMPHORAE**

An amphora (pl. amphorae) is a two handled storage pot. There are two common types: neck amphorae, which have a clearly defined neck distinct from the rest of the shape, and belly amphorae, which have a continuous shape. (“Amphorae.”)

Standard Neck Amphora:  
<img src="https://www.beazley.ox.ac.uk/images/pottery/shapes/bt14-17s.jpg"/>   
("Athenian Standard Ht. 38cm,” image from *Classical Art Research Centre*)

Common Belly Amphora (*Type B*):  
<img src="https://www.beazley.ox.ac.uk/images/pottery/shapes/bt7-19s.jpg"/>   
("Type B Amphora," image from *Classical Art Research Centre*)

For our research, we combined Type A, Type B, and Type C amphorae under a “belly amphora” category (“Belly amphora.”) and neck amphorae, shoulder-handled amphorae, and neck psykter-amphorae under a “neck amphora” category in order to examine patterns in distribution. In preparing the data, we discarded 817 panathenaic amphorae. Panathenaic amphorae were given to the winners of the Panathenaic Games as vessels for the prize oil they carried (“Panathenaic prize amphora.”). The distribution pattern of the panathenaic amphorae would thus not have been influenced by the same trade factors as other amphorae. We additionally discarded 173 entries with unspecified amphora shapes. Because these entries did not clearly fall into either the belly or neck categories, they were removed from the data set. The cleaned amphora data set contained 1,994 neck amphorae, 1,114 belly amphorae, and three bail amphorae.

There is a large quantity of neck amphorae, a moderate quantity of belly amphorae, and a very small quantity of bail amphorae. The distribution patterns for the neck amphorae are generally similar to the krater distribution patterns, seen later. The neck amphorae has the widest distribution patterns compared to the belly and bail amphorae. The central location for the neck amphorae seems to have been in Italy, specifically in or around Rome. In Greece, Athens is the most densely clustered location of neck amphorae find spots. There is additionally a large cluster around Etruria; the Classical Art Research Centre notes that Etruria was likely the intended market for certain kinds of neck amphorae (“Neck-Amphora.”). The belly amphorae find spots are scattered, but have small clusters in Italy, one main cluster in Greece, and several find spots in modern-Turkey. The high density clusters of find spots for both neck and belly amphorae are in similar areas but there are a greater number of find spots identified for neck amphorae, which is likely correlated to the greater number of neck amphora found. Lastly, due to the limited quantity of bail amphorae we can not make solid claims about the distribution pattern of that particular shape. The three bail amphoras identified were found in three spots near Athens. Bail amphorae are distinct from neck and belly amphorae in that they have one handle over the top of the vase’s opening. Perhaps this distinct shape was specific only to the region around Athens.

Neck Amphora:
<img src="https://github.com/nadimattia/clas299/blob/master/beazley_finalproject/qgis_images/neck_amphoras_image.png?raw=true"/>
(*original image created by the authors*)

Belly Amphora:
<img src="https://github.com/nadimattia/clas299/blob/master/beazley_finalproject/qgis_images/belly_amphoras_image.png?raw=true"/>
(where pink = Type B, red = Type A, purple = Type C, *original image created by the authors*)

**KRATERS**

We additionally extracted 5,575 krater entries. As with the amphora data, 1,087 kraters with unspecified shapes were discarded in order to focus on the four common shapes: calyx, column, bell, and volute. Column and bell kraters were the most common with approximately 1,800 of each found. 599 calyx kraters and 266 volute kraters were additionally identified. Kraters were a mixing vessel used to dilute wine with water. In Greek overseas colonies, they were additionally often used as grave markers and to hold ashes, especially volute kraters (“Kraters.”)

Krater Shapes:  
<img src="https://www.beazley.ox.ac.uk/images/pottery/shapes/Kraters3.jpg"/>  
("Kraters," image from *Classical Art Research Centre*)

Column kraters are the most common krater shape, with 1,852 identified. We found that the column krater data points that we mapped in QGIS are  more concentrated in certain geographical locations. The highest concentrated areas are located in Rome, Athens, and Sicily. In terms of classical locations, the data points are additionally concentrated where  Cumae, Amphipolis, and Metapontum were located. As seen below, there appears to be considerably more data points in Italy compared to Greece. The small number of outliers on the map span from modern-Spain all the way to modern-Syria.
<img src="https://github.com/nadimattia/clas299/blob/master/beazley_finalproject/qgis_images/column_krater_image.png?raw=true"/>  
(column kraters, *original image created by the authors*)

Bell kraters are the second most common and are distributed across most of the Mediterranean. The find spots are clustered in many areas. Some of the most densely clustered areas include: Rome, Athens, Cyprus, Crete, Sicily, and the coast of Spain. We also noticed that there was a reasonable amount of data points located where Etruria was. Locations that have a lower concentration of points are nearby Alexandria, Crete, and Israel. Along with the column kraters, bell kraters have the widest distribution patterns seen amongst krater shapes. They have the highest number of find spots outside Greece and Italy compared to the other shapes.  
<img src="https://github.com/nadimattia/clas299/blob/master/beazley_finalproject/qgis_images/bell_kraters_image.png?raw=true"/>  
(bell kraters, *original image created by the authors*)

The find spots of the calyx kraters are clustered, however, these clusters are much smaller than those the column and bell kraters displayed. There are four main clusters visible on the map located in Rome, Athens, Naples, and the eastern part of Sicily. There is a smaller quantity of these kraters located in Greece. The calyx kraters are not distributed as widely as the column and bell kraters. The kraters were found very far east, but did not spread out to the west. To compare, the bell kraters find spots spread to both the eastern and western parts of the Mediterranean.
<img src="https://github.com/nadimattia/clas299/blob/master/beazley_finalproject/qgis_images/calyx_kraters_image.png?raw=true"/>  
(calyx kraters, *original image created by the authors*)

Volute kraters have similar distribution patterns to calyx kraters. There are less volute kraters than calyx kraters, but are clustered in relatively the same areas. A large portion of the volute kraters were found in Southern Italy. Volute kraters in Southern Italy often were often found in grave-sites holding ashes and have specific funeral iconography (“Kraters.”) There are a few outliers, which can be found in Germany and southern Egypt.  
<img src="https://github.com/nadimattia/clas299/blob/master/beazley_finalproject/qgis_images/volute_kraters_image.png?raw=true"/>  
(volute kraters, *original image created by the authors*)

**CONCLUSION**

We aimed to discover potential connections between different variations of kraters and amphorae and their distribution patterns. There was a visible difference in the distribution among krater shapes, especially when comparing column and bell kraters against calyx and volute kraters. This difference in distribution could indicate a number of trade factors: preference of certain cultures toward certain shapes, trade patterns during different time periods, or differences in use by culture, such as funerary practices in the case of the volute krater. Column and bell kraters seem to be the most universally used shapes in the ancient world, despite column kraters being the oldest krater shape and bell krater being the newest to emerge. Neck-amphorae and belly amphorae did not differ greatly in their distribution patterns. If one were to break down the belly amphorae into further categories (Type A, Type B, Type C), distinct patterns might be visible among those shapes. Future researchers could develop this research question further by examining the distribution patterns amongst a wider range of shapes. Additionally, further research into the dates of the pottery could reveal more about the historical events that could have affected trade and distribution of the pottery.

*Works Cited:*

“Amphorae.” Classical Art Research Centre, Classical Art Research Centre, 2018, www.beazley.ox.ac.uk/tools/pottery/shapes/amphorae.htm.

Beazley, John. Beazley Archive Pottery Database, Classical Art Research Centre, 1998, www.beazley.ox.ac.uk/XDB/ASP/searchOpen.asp.

“Belly amphora.” Classical Art Research Centre, Classical Art Research Centre, 2018, www.beazley.ox.ac.uk/tools/pottery/shapes/belly.htm.

“Kraters.” Classical Art Research Centre, Classical Art Research Centre, 2018, www.beazley.ox.ac.uk/tools/pottery/shapes/kraters.htm.

“Neck Amphora.” Classical Art Research Centre, Classical Art Research Centre, 2018, www.beazley.ox.ac.uk/tools/pottery/shapes/neck.htm.


“Panathenaic prize amphora.” Classical Art Research Centre, Classical Art Research Centre, 2018, www.beazley.ox.ac.uk/tools/pottery/shapes/panathenaic.htm.

“The Beazley Archive.” Beazley Archive, Classical Art Research Centre, 2016, www.beazley.ox.ac.uk/archive/default.htm.

*Images Cited:*

“Athenian Standard Ht. 38cm.” Classical Art Research Centre, Classical Art Research Centre, 2018, www.beazley.ox.ac.uk/images/pottery/shapes/bt14-17s.jpg.

“Type B Amphora.” Classical Art Research Centre, Classical Art Research Centre, 2018, https://www.beazley.ox.ac.uk/images/pottery/shapes/bt7-19s.jpg.

“Kraters.” Classical Art Research Centre, Classical Art Research Centre, 2018, https://www.beazley.ox.ac.uk/images/pottery/shapes/Kraters3.jpg.
