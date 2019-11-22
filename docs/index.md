## QGIS

## What is a Geographic Information System (GIS)?

It's computer software that lets you visualize, manipulate and analyze data that has some type of geographic element.

More information and examples from [National Geographic](https://www.nationalgeographic.org/encyclopedia/geographic-information-system-gis/).

## Types of "features"

Working with GIS software, you'll encounter three primary types of "shapes":
* Points
* Lines
* Polygons

![Feature examples](/images/features.jpg)
_Image credit: [Essentials of Geographic Information Systems](https://saylordotorg.github.io/text_essentials-of-geographic-information-systems/index.html)_

### Points

Individual locations on a map, each with a set of geographic coordinates.

### Lines

Geographic data that connects two points in space together; that connection can be a straight line that covers the shortest distance possible, or it can curve or zig-zag back and forth. Thinks roads, rivers and aviation flight paths.

### Polygons

Enclosed shapes that represent a geographic area. Think countries, states, municipal boundaries and real estate parcels.

## Projections

One challenge in mapping is that you're representing geographic points and shapes that sit on the surface of a sphere. When making a map, you're flattening those curves into two dimensions.

A __geographic coordinate system__ "uses a three-dimensional spherical surface to define locations on the earth ([Esri](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#/What_are_geographic_coordinate_systems/003r00000006000000/))." It's not "projected," so GIS software defaults to a [geographic projection](https://en.wikipedia.org/wiki/Equirectangular_projection), which treats latitude and longitude lines as a perfect grid — this stretches and distorts locations the closer to the poles you get (see bottom right example below.)

Common geographic coordinate systems (named after the datum that tracks latitude and longitude): `WGS 84`, `NAD 83`

A __projected coordinate system__ is designed to account for this flattening; you'll use a different projection depending on what you're looking at. For a world map, you're going to want to use a projection that shows a fairly undistorted view of all the different landmasses across the globe. For a map of Syracuse, though, you'd want to use a projection designed to accurately portray Central New York.

Common projected CRS in the U.S.: `Albers Equal-Area Conic`, `Universal Transverse Mercator (UTM)`

For more:
* [How to pick a map projection](https://source.opennews.org/articles/choosing-right-map-projection/)
* [What are geographic coordinate systems?](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#/What_are_geographic_coordinate_systems/003r00000006000000/)
* [Map projection types](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#/Projection_types/003r0000000r000000/)


![Example of map projections](/images/proj.jpg)
_Image credit: Michael Corey_

## Making a basic thematic map

TK
