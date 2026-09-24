# New Orleans bike-lane reports and enforcement

[Open the interactive map](https://adamdavies.dev/nola-bike-lane-enforcement/)

A public-data comparison of Bike Lane Uprising vehicle-obstruction reports and New Orleans parking tickets coded `154.923(17)` (“parked within a bicycle lane”).

The default comparison covers January 2025–July 2026. Separate 2025 and January–July 2026 views are available. Data was retrieved September 24, 2026.

The map highlights potential enforcement mismatches, not proof that officers ignored complaints. Reports and tickets are independent observations, reporting intensity varies, and other ticket codes may apply. Ambiguous street matches are excluded from the headline report counts. Ticket markers represent approximate hundred-block locations, not exact ticket coordinates.

## Site files

- `docs/index.html`: interactive map with embedded report, ticket-summary, and street-geometry data.
- `docs/methodology.html`: findings, matching rules, exclusions, and sensitivity checks.
- `docs/blu_new_orleans.geojson`: original New Orleans-tagged public BLU report features.

GitHub Pages publishes from `main`, `/docs`. No build step is required. The map library loads from a CDN; report photos remain hosted by the source organization.

## Sources

- [Bike Lane Uprising map](https://www.bikelaneuprising.com/maps/all)
- [BLU public pin data](https://feed.bikelaneuprising.com/maps-data/cities/all/all.json)
- [New Orleans road centerlines](https://gis.nola.gov/arcgis/rest/services/Transportation/RoadCenterline/MapServer/0)
- [City DPW parking dashboard](https://app.powerbigov.us/view?r=eyJrIjoiYjRlYTNkZjYtM2RlOC00ZjNjLWJhOWItMjc0ZWJlODNmZjg5IiwidCI6IjA4Y2JmNDg1LTFjYjctNGEwMi05YTIxLTBkZDliNDViOWZmNyJ9)

This is an independent analysis, not an official City of New Orleans or Bike Lane Uprising publication. Source data and images remain subject to their respective owners' terms; this repository does not relicense them.
