# GURS meje občin v Sloveniji / Municipalities borders in Slovenia

Občine v Sloveniji 2020

## Vir podatkov

Geodetska Uprava Republike Slovenije
Dovoljenje: CC-BY 2.5
https://egp.gu.gov.si/egp

## Source data

The Surveying and Mapping Authority of Republic of Slovenia
Licence: CC-BY 2.5
https://egp.gu.gov.si/egp/?lang=en

## Tehnične podrobnosti / Technical details

Ukaz pretvorbe izvorne datoteke / Source onvertion command:

```bash
SHAPE_ENCODING=CP1250 ogr2ogr -progress -t_srs "EPSG:4326" -f "GeoJSON" ./Obcine-epsg4326.geojson ./RPE_PE/OB -nln Obcine-epsg4326 -lco ENCODING=UTF8
```
