getflickr
=========

Bash script which combines some command line tools to download photos from flickr georss feed with their exif intact.

I'm using this: http://commons.wikimedia.org/wiki/User:InverseHypercube/flickr_exif.py
Save it in a file called exif.py, remember to install dependencies: python flickr api and exiftool.


FLickr GeoRSS feed: http://api.flickr.com/services/feeds/geo


Install:
--------

First install Exiftool:

$ sudo apt-get install libimage-exiftool-perl 

$ sudo apt-get install python-flickrapi

Open up text editor and copy the script at:
http://commons.wikimedia.org/wiki/User:InverseHypercube/flickr_exif.py
Just name it exif.py. 
To run it: python exif.py <picture ID>
e.g: 
$ python exif.py 4083220012

You can also provide multiple flickr picture ID's as arguments.

