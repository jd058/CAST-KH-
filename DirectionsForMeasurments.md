# CAST-KH-
CAST KH Research
1)	Go to EarthExplorer (usgs.gov)
2)	On the Search Criteria Tab, under the Polygon subtab, click use map. 
3)	Once you have your designated map, move to the Data Set tab at the top of the page and click the + sign on Declassified Data
4)	Choose between Declass 1 (KH-4/KH-4A/KH-4B), Declass 2 (KH-9 Mapping), or Declass 3 (KH-9 Panoramic) and then press Results
5)	Each Image should start with a Footprint Symbol, this will allow you to see the image. There should also be an icon that has a Green Arrow Pointing Downward- that symbol will allow you to download. 
6)	Once downloaded, move the file to correct destination within your file explorer (This Pc / Local Disk(C:) / Data / KH) You can then designate if it’s a KH-9 Mapping, KH-9 Panoramic, KH-4, KH-4A, or KH-4B. Right click on the downloaded image and Select 7-Zip and the Extract Files.
7)	There should now be a replica File with the Letter T instead of the 92 at the top of the file. Extract the files once more. 
8)	This should now just be a file with the images inside. 
9)	Open SOCET GXP
10)	Drag one of the images from File Explorer into SOCET GXP Workspace Manager. The Image should say type TIFF.
11)	Right click on the TIFF image in SOCET, go down to Geopositioning, and then click Registration
12)	A Multiport Panel and a Registration Panel should appear. Go to the Registration Panel and on Transformation Type, click the down arrow and select 2D Direct Linear Transform (4 Point Minimum). 
13)	Open Google Earth Pro
14)	On Google Earth Pro, go to the location of the selected image. Most images will appear upside down in SOCET so you may want to have North point towards the South to help.
15)	Locate points distinguishing features in the four corners of the map to the best of your ability. 
16)	On Google Earth Pro, use the Yellow Placemark to pin the coordinates. You can then copy and paste those into Registration, however you have to delete any symbols besides the integers and decimals. 
17)	At the bottom corner of Google Earth, you can see the elevation in feet. Convert it that to meters and plug it into the Registration. 
18)	In Registration, click on the point and press Enter Point Selection Mode. Place the point in the Multiport that would be the same in Google Earth. 
19)	Repeat for all corners. Once done press Register, a fifth point should appear with blank boxes. Then press Accept. Save the file and exit the Multiport and Registration. Press no when it ask to save the Registration.
20)	There should be a SUP file in SOCET GXP Workspace Manager. Right click the SUP File, go to Geopositioning, Triangulation, and then Press Triangulation Overview. 
21)	A tab called Geospatial should be at the top of the Triangulation Overview. Then click ground points. Press Enter Point Selection. You can now select a point in the Overview and should place a mark in Google Earth and they should be relatively close to the same coordinates.
22)	You can now ground points, you do not have to save them. On the Overview, select the Home tab. Press Add Tile Point, XYZ Control Point, and then place a mark. You can now exit out of the Triangulation Overview and save it to the correct folder. 
23)	Right click on the SUP and TIFF file and unload both from the Workspace Manager. Go back to Step 10 and repeat until all images are completed. 
24)	Once you are done go back to EarthExplorer to the search criteria tab and press clear coordinates. Repeat step 2.
