# gpxCreator
testing gpx stuff

## gpxcreator.js
you need to use nodejs to run this file. Change the source code to add new gpx coordinates in string form.

This file was created to extract gpx data from relive.cc website. How do you do it on your own? Use the debugger/inspect tool in Chrome/Firefox to open the source file tree. There should be one generated html file under view/***. This file name is autogenerated so should have some random alphabet as filename. Search in that file to find this line:
`var positions = [[45.3434, 42.2323], [.....]];`

copy that line from that file to this source file to output a .gpx file. 

Run it as
`node gpxcreator.js > output.gpx`

