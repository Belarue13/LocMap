# LocMap
Software to read a file with location information (longitude latitude) and calculates the  distance between 2 locations. Can also add to the database (locations.txt)

Requires JDK 20+ to run!

The program asks for a file name, this is the file where it reads the longitude and latitude information for each location. The file is formatted as follows:
[location name]
latitude
longitude

After selecting the file, you'll see:
F/C/A/E

F - Find
  Find the latitude and longitude of a location stored in the selected file.
C - Calculate
  Estimate the distance between 2 locations stored in the selected file (by miles).
A - Add
  Add a location to the selected file (requires name, latitude, and longitude).
E - Exit
  Close the program.
