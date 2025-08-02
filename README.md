# Toronto GeoJSON (2025)

This repo contains a processed GeoJSON file based on Toronto’s Forward Sortation Areas (FSAs) for 2025. 
  
## Data Sources
- **Shapefile**: 2021 FSA boundaries from Statistics Canada  
  [Boundary files (2021 Census)](https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/boundary-limites/index2021-eng.cfm?year=21)
- **FSA Mapping**: FSA → borough & neighborhood from Wikipedia  
  [List of postal codes of Canada: M](https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)

## Processing steps
1. Downloaded the 2021 FSA shapefile from Statistics Canada.
2. Converted & simplified to GeoJSON.
3. Joined FSA codes to borough & neighborhood names from the processed dataframe from Wikipedia.

## Files
- `toronto-fsa-2025.geojson` – processed GeoJSON

---
Notes: This file has been filtered based Government of Canada Forward Sortation Area Definition in which Toronto FSA starts with letter 'M'.
* Source:  https://ised-isde.canada.ca/site/office-superintendent-bankruptcy/en/statistics-and-research/forward-sortation-area-fsa-and-north-american-industry-classification-naics-reports/forward-sortation-area-definition
---
#### Disclaimer
<sub>This project is for educational and training purposes only. Efforts were made to ensure data accuracy using public sources, but the results may include simplifications or errors. Not affiliated with any official agency. Use at your own discretion.</sub>
