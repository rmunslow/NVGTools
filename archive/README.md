NVGTools
========

NATO Vector Graphic Tools.

This tool was developed in response to a customer request working with NVG files created in iGeoSit.

The tool will take version 0.3, 1.4 and 1.5 of NVG and create points, lines and polygons within a 
ESRI file geodatabase.

The code is not the most efficient and I have a lot of tidying up to do. It was created in about half a day to 
get a working solution out to the customer.

I will update as often as I can but please feel free to take the code and use / improve.

There are a number of functions added within the .pyt file that convert between lat/lon and MGRS / UTM. These 
are a port of some vba modules I used before and I have little understanding of the maths behind. The results 
have been tested against a number of different converters and work well. There is a small glitch with invalid MGRS 
coordinate strings returned if the x or y coordinate is less than 10000. There is a qquick fix in place but it needs
more work.

This tool set is obsolete and will be replaced by the new reader and writer code being developed in the main branch.
