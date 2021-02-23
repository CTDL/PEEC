# PEEC
Pajarito Environmental Education Center

# Project Details
Convert existing iOS and Android applications into cross platform React Native application

Application uses Mapbox to host trail data. 

Mapbox | https://docs.mapbox.com/help/glossary/maps-sdk-for-react-native/

Due to upload size constraints of Mapbox studio, Geojson files are converted into a .mbtiles file using Mapbox tool Tippecanoe. Each trail is a layer in the .mbtiles file.

Tippecanoe | https://github.com/mapbox/tippecanoe

```
$ tippecanoe -o peec.mbtiles -zg file.json file.json 
```
