# Mini geocoding system
By: Nur Rochman Muhammad

### Objective:
My objective only to prove my couriousity about geocoding.

This way of thinking could be used for someone who need to reduce paid geocoding services by reuse their geocoding history or someone has big data address and lat/long pairs.

### How it works

We input address keyword, then we get a result hexagon, point, and heatmap that (indicate confidence level of address we are looking for)

### Dataset
I used reverse geocoding service from nonatim/ osm (free).

#### My idea is to creating / replicate geocoding (pair of address and coordinate) to create small geocoding system based on historical geocoding from osm services.

1st step: I define test area,(DKI Jakarta), then resample that area into point grid.

2nd. step: Do geocoding process of grid latlong.

3rd. step: grouping those points by hexagon and labelling each group of points using hexagon id.

4th step: build matching keyword system for our address library to find which hexagon contained our address/location that we try to find.
