# JaxVoterOutput

An interactive HTML map of Duval County, Florida, showing November 5, 2024 general election turnout and Census demographic estimates.

## Open the map

Download `index.html` and open it in a browser. The map data and Leaflet library are embedded, so the map works offline. The optional OpenStreetMap background requires internet access.

## Layers

- **Voter turnout:** ballots cast divided by registered voters, across 160 election precincts.
- **Race and ethnicity:** population percentages across 218 Census tracts, using 2020–2024 American Community Survey five-year estimates.
- **Sex:** ACS male and female population percentages. ACS measures sex rather than gender identity.

Select a topic and category, click an area for details, or use the area selector. Each layer supports a data table and CSV download. Demographic details include 90% margins of error.

## Sources and interpretation

- [Duval County official 2024 election map and results](https://enr.electionsfl.org/DUV/3694/Map/PrecinctsReporting/)
- [Election-specific precinct boundaries](https://s3.amazonaws.com/results.voterfocus.com/enr/maps/DUV/3694/map.kml)
- [ACS Race and Hispanic Origin, distributed by Esri](https://www.arcgis.com/home/item.html?id=727c1ec5018a40cf98ea262e09005929), Census table B03002.
- [ACS Population, distributed by Esri](https://www.arcgis.com/home/item.html?id=60c98f20a162416ea1725b94d7297f83), Census table B01001.

Data snapshot: September 25, 2026. Both ACS sources identify their vintage as 2020–2024.

Turnout uses voting precincts; demographics use Census tracts. Values have not been transferred between these boundaries. Demographics describe all residents, including children, rather than people who voted. Hispanic/Latino includes any race; other displayed race categories exclude Hispanic/Latino residents. See the map's Sources & methodology section for further details.

County election totals reconcile to 476,074 ballots and 649,929 registered voters. Demographic category counts were checked against tract population totals. Layer controls, area selection, tables, and CSV download were browser-tested.

## Third-party software

This file embeds Leaflet 1.9.4, licensed under the BSD 2-Clause License. See `THIRD_PARTY_NOTICES.md`.
