# SignalK Harbour Regions

Shared harbour data for AIS Plus automatic profile switching.

## Files

- `west-scotland-harbour-points.csv` - seed point locations for west-coast Scotland harbours, marinas, pontoons, and commonly used small-craft stops.

## Data Notes

This is not yet a finished AIS Plus harbour-region file. It is a seed list for
creating and checking harbour polygons.

Rows marked `openstreetmap` came from OpenStreetMap/Overpass harbour or marina
tags. Rows marked `manual_seed` are useful cruising-guide candidates added by
name and approximate position, and should be checked before creating a polygon.

The next step is to turn selected points into `Harbour:` region polygons using
Harbour Editor, then export those polygons to `harbours.json`.
