# Toronto GeoJSON (2025)

This repository contains a processed GeoJSON file based on Toronto’s Forward Sortation Areas (FSAs) for 2025. It merges geographic boundaries with borough and neighborhood information for mapping and analysis purposes.

---


## How to Clone This Repository
To work with this project locally:

1. Copy the repository URL:  
```bash
https://github.com/This-is-Leo/toronto-geojson-2025.git
````

2. Open your terminal and navigate to your desired folder:

```bash
cd path/to/your/folder
```

3. Clone the repository:

```bash
git clone https://github.com/This-is-Leo/toronto-geojson-2025.git
```

## Data Sources
- **Shapefile**: 2021 FSA boundaries from Statistics Canada  
  [Boundary files (2021 Census)](https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/boundary-limites/index2021-eng.cfm?year=21)
- **FSA Mapping**: FSA → borough & neighborhood from Wikipedia  
  [List of postal codes of Canada: M](https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)

---

## Processing Steps
1. Downloaded the 2021 FSA shapefile from Statistics Canada.  
2. Converted and simplified the shapefile to GeoJSON.  
3. Merged FSA codes with borough and neighborhood names using a processed dataframe from Wikipedia.

---

## Files
- `toronto-fsa-2025.geojson` – processed GeoJSON file ready for mapping and analysis.

---

## Notes

This file has been filtered based on the Government of Canada Forward Sortation Area definition, where Toronto FSAs start with the letter **'M'**.

* Source: [Government of Canada FSA Definition](https://ised-isde.canada.ca/site/office-superintendent-bankruptcy/en/statistics-and-research/forward-sortation-area-fsa-and-north-american-industry-classification-naics-reports/forward-sortation-area-definition)

---
## Disclaimer

<sub>This project is for educational and training purposes only. Efforts were made to ensure data accuracy using public sources, but the results may include simplifications or errors. Not affiliated with any official agency. Use at your own discretion.</sub>
---
