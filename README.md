# Geonet x Google Earth API



HOST: http://www.pixieplots.co.nz/shit/q/kml.php

## 3DGeonet

Retreive Quake data from Geonet and format as 3D kml for google earth

## Quakes [/{?start,end,magmin,magmax,depthLower,depthUpper,setbounds,boundsv}]

+ Parameters
    + start  (optional) - start date - 
        default: -24hours
    + end (optional) - end date
        default: now
    + magmin (number, optional) - minimum magnitude
    + magmax (number, optional) - max magnitude
    + depthLower (number, optional) - minimum depth
    + depthUpper (number, optional) - max depth
    + setbounds (number,optional) - 1 to set bounds
    + boundsv (optional) - lat/long rectangle

### List Quakes [GET]

+ Response 200 (text/html)

        <kml xmlns="http://www.opengis.net/kml/2.2">
            <Document>...</Document>
        </kml>

Check out our [documentation](https://pixieplots.docs.apiary.io/#) and API blueprint
