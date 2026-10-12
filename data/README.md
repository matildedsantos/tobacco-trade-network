# Data

| File | Content | Source |
|---|---|---|
| `comtrade_hs240120_exports_2023.csv` | Raw extract: exports of HS 240120, 2023, all reporters and partners (1,088 rows, 47 columns) | UN Comtrade |
| `country_coordinates.csv` | Latitude and longitude of each country's capital, by ISO3 code. `S19` (Other Asia, nes) is placed at an approximate central point in Asia | SimpleMaps World Cities (2024) |
| `world_land_110m.geojson` | Land outline used as the map background | Natural Earth 1:110m (public domain), via the `world-atlas` package |

UN Comtrade query used: Trade flow = Export, Reporters = all, Partners = all, Year = 2023, Commodity = 240120, all modes of transport.
`NetWgt` is in kilograms and `PrimaryValue` in US dollars.
