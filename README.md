# gravity.distances_data

Data for the [gravity.distances](https://github.com/julianhinz/gravity.distances) R package. Please check out [julianhinz.com/resources/#gravity.distances](http://julianhinz.com/resources/#gravity.distances) for more information.

## Currently available distance datasets
| Name | Description |
| --- | --- |
| distances_from_countries_to_countries | Distances between 193 countries, for the years 1992 – 2012 and &theta; &isin; {-2,1} |
| distances_from_usa_states_to_countries | Distances between 192 countries and 50 US States, for the years 1992 – 2012 and &theta; &isin; {-2,1} |
| distances_from_usa_states_to_usa_states | Distances between 50 US States, for the years 1992 – 2012 and &theta; &isin; {-2,1} |
| distances_from_canada_provinces_to_countries | Distances between 192 countries and 13 Canadian provinces and territories, for the years 1992 – 2012 and &theta; &isin; {-2,1} |
| distances_from_canada_provinces_to_canada_provinces | Distances between 13 Canadian provinces and territories, for the years 1992 – 2012 and &theta; &isin; {-2,1} |
| distances_from_canada_provinces_to_usa_states | Distances between 50 US States and 13 Canadian provinces and territories, for the years 1992 – 2012 and &theta; &isin; {-2,1} |

## Known issues
* Geometric mean distances (&theta; = 0) missing in some of the datasets
* Missing distances from Canadian provinces to country "USA" and from US states to country "CAN"
