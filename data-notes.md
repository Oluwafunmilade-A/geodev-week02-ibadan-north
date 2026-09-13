# Data notes

## Nigeria LGA Boundaries

- Source: geoBoundaries
- Source link: https://www.geoboundaries.org/
- Dataset: Nigeria ADM2 administrative boundaries
- Features: 773
- Key columns: Name, Level, adm, adm_int, feature_id, gbid, iso
- Geometry: Polygon
- Study area: Ibadan North LGA
- Coverage: The dataset provides LGA administrative boundary coverage across Nigeria.

## OSM Roads - Ibadan North

- Source: OpenStreetMap via QuickOSM
- Source link: https://www.openstreetmap.org/
- Query: highway, all values, using the Ibadan North layer extent
- Extracted: 13 September 2026
- Features: 4,560
- Geometry: Line (LineString)
- Key columns: fid, full_id, osm_id, osm_type, highway, name, surface, oneway, maxspeed
- Nulls: Many optional road attributes contain NULL values, and some road features have no recorded name.
- Coverage: Coverage appears good across Ibadan North, with a dense road network and no obvious major gaps within the study area.