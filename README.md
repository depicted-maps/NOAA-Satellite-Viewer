# NOAA Satellite Viewer

## Purpose

<p align="justify">
The NOAA Satellite Viewer repository provides a centralized collection of web-based satellite imagery viewers for environmental observation, weather monitoring, and geographic visualization. The viewers are designed for use in standard web browsers and integration with ArcGIS StoryMaps and other geographic information system applications.
</p>

This repository is maintained by **depicted-maps**.

## Satellite Viewers

### GOES-19

**Status:** Initial satellite imagery viewer.

<p align="justify">
The GOES-19 viewer provides a responsive interface for displaying NOAA geostationary satellite imagery. The application is designed to maintain the original image proportions while adapting to different screen dimensions, including embedded presentations within ArcGIS StoryMaps.
</p>

Additional satellite viewers may be introduced as imagery sources become available and project requirements expand.

## Viewer Design Requirements

All satellite viewers will follow consistent presentation standards:

- Display the complete intended satellite imagery.
- Preserve the original image aspect ratio.
- Prevent image stretching or distortion.
- Support responsive scaling across screen sizes.
- Support embedding within ArcGIS StoryMaps.
- Maintain readable titles and labels at different display sizes.
- Display NOAA identification and appropriate source attribution.
- Document satellite imagery sources and refresh procedures.
- Maintain stable viewer addresses whenever possible.

## GitHub Pages

The repository website will be published at:

https://depicted-maps.github.io/NOAA-Satellite-Viewer/

The planned GOES-19 viewer address is:

https://depicted-maps.github.io/NOAA-Satellite-Viewer/GOES-19/

These addresses will become available when the corresponding files are deployed through GitHub Pages.

## Maintenance and Governance

<p align="justify">
Each satellite viewer will be maintained independently within the NOAA Satellite Viewer repository. New viewers may be introduced without modifying existing applications or disrupting published links. All viewers will follow consistent presentation, attribution, responsive design, and documentation standards.
</p>

## Future Expansion

<p align="justify">
The repository is designed to accommodate additional geostationary and low-Earth-orbit satellite imagery viewers as operational requirements evolve. New satellite viewers will be added only when needed, maintaining a simple and scalable repository organization.
</p>
