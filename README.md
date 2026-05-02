# SignalK Harbour Regions

> **Alpha Release disclaimer:** This software is Alpha Release and has not been tested in live environments and must not be relied upon for navigation or safety. The Authors do not accept any responsibility for loss or damage as a result of using this software.

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
