# osm-grab

> cli utility for grabbing OSM XML from OSM.org

## Usage

```
$ osm-grab
USAGE: osm-grab LAT LON RADIUS-KM

$ osm-grab 37.7274 -122.1134 0.2
<?xml version="1.0" encoding="UTF-8"?>
<osm version="0.6" generator="CGImap 0.6.0 (1918 thorn-03.openstreetmap.org)" copyright="OpenStreetMap and contributors" attribution="http://www.openstreetmap.org/copyright" license="http://opendatacommons.org/licenses/odbl/1-0/">
 <bounds minlat="37.7264000" minlon="-122.1144000" maxlat="37.7284000" maxlon="-122.1124000"/>
 <node id="1255996675" visible="true" version="1" changeset="7939120" timestamp="2011-04-22T21:55:51Z" user="DanHomerick" uid="160138" lat="37.7301010" lon="-122.0890293"/>
...
```

## Install

With [npm](https://npmjs.org/) installed, run

```
$ npm install --global osm-grab
```

## License

ISC

