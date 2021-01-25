# Adventures in Mapping

Notes and tutorials to help you map things in the real world.

***This is still VERY MUCH a WORK IN PROGRESS***

## Where Things Live

[OpenStreetMap](https://www.openstreetmap.org) is a global map of the world, created by a huge open community.  It stores things that anyone could find "on the ground" if they visited the spot.  There's some more background on the OpenStreetMap wiki [How We Map](https://wiki.openstreetmap.org/wiki/How_We_Map) page.

If you want to map things that are more personal, or specific to a particular project, then you should store that information somewhere else.  That could be one of the projects *related* to OpenStreetMap, for example, [umap](https://umap.openstreetmap.fr) or on your own website.  You might still use the underlying OpenStreetMap tiles to show the general map, and then overlay your information on top of it.

## How to...

 * Add data to OpenStreetMap - there's a quick guide to [adding some bike parking (for example)](https://www.youtube.com/watch?t=7598&v=7PFweb6ibW8&feature=youtu.be) in that longer video (which will feature again later...).  The [OpenStreetMap Wiki](https://wiki.openstreetmap.org/) has lots of details of the tags to use and what their different values mean.  Some we've used, to give some examples:
   * [`garden:type`](https://wiki.openstreetmap.org/wiki/Key:garden:type)
   * [`landuse=allotments`](https://wiki.openstreetmap.org/wiki/Tag:landuse%3Dallotments)
   * [`natural=tree`](https://wiki.openstreetmap.org/wiki/Tag:natural%3Dtree)
   * [`man_made=planter`](https://wiki.openstreetmap.org/wiki/Tag:man_made%3Dplanter)
   * [`amenity=bench`](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dbench)
   * [`amenity=bicycle_parking`](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dbicycle_parking)
 * Build a map of data not in OpenStreetMap - [umap](https://umap.openstreetmap.fr) works well for this:
   * Place markers to show points of interest, which pop up description boxes when clicked on
   * Group items into layers to let people easily toggle visibility of them on/off
   * Draw lines to show routes or walks
   * Pull in live data from OpenStreetMap to make it more visible - [this video shows that process to make a map of park benches or bike parking](https://www.youtube.com/watch?v=7PFweb6ibW8)
 * Track your location with your phone, with the Osmand app and its trip recording plugin.  Then you  can save the track and later upload it to umap to share it with others
 * Capture map info for OpenStreetMap on paper (to then bring into OpenStreetMap on a computer later), with [FieldPapers](http://fieldpapers.org/)

## Other Interesting Links...

 * [Leafletjs](https://leafletjs.com/) is a useful Javascript library for adding mapping to custom websites
 * [MapKnitter](https://mapknitter.org/) makes it easy to overlay aerial photos taken from balloons or drones and position them correctly for use in other mapping software
 * [OpenAerialMap](https://map.openaerialmap.org/) lets you use your own aerial imagery (maybe created with the help of MapKnitter) when mapping in OpenStreetMap
