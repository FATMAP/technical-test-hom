# Head of Mapping - Technical Task

Thanks for applying to work at FATMAP. We have developed this small task for you
to work on in your own time so that we can see how you approach tasks and as a
discussion point going forwards.

Try not to spent more than half a day on this task in total - and don't worry if
it is not complete, we prefer to see quality over quantity.

## The task

We want to find all available imagery in the Digital Globe catalogue which
intersects an area around Chamonix and which was captured between October 2016
and April 2017 inclusive. 

The `aoi.geojson` file defines our area of interest.  Using this and the date
range as input, connect to [GBDX](https://gbdxdocs.digitalglobe.com/) using the
[`gbdxtools`](http://gbdxtools.readthedocs.io/en/latest/index.html) Python
module and retrieve all matching records from the catalogue. The records should
be saved in GeoJSON format and should contain at a minimum properties
representing the GBDX `catalogID`, `platformName` and `timestamp`.

## Notes

* You will need to create a
  [free evaluation account](https://gbdxdocs.digitalglobe.com/v1/page/try-gbdx-for-free) on the GBDX
  platform.

* Please submit your code with an overview document describing how to run it and
  any dependencies that might need to be installed.

* Bonus points if the script can run in the QGIS Python console and
  automatically add the records as a new layer :).
