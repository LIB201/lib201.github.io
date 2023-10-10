---
title: "First Steps into GIS"
author: "DH 131: Spring 2023, Class 2"
format:
 revealjs:
  preview-links: true
  logo: images/CC_BY-SA_icon.svg
title-slide-attributes:
 data-background-color: "#005c96"
 data-background-size: 6%
 data-background-position: 100% 100%   
---

## Overview {data-background="#005c96" }
- Brief History of Spatial Analysis
- GIS / QGIS
- Spatial Data Formats
	- Raster, Vector
- Ending : Data!

## What is a Map? {data-background="#005c96" }

## Çatalhöyük {data-background="#005c96" }
![](images/chat-1.png)

## Çatalhöyük {data-background="#005c96" }

![](images/chat-2.jpeg)

## {data-background="#005c96" }

- c. 6790 - 6430 BCE
- Çatalhöyük, Turkey
- Square-shaped patterns, interpreted as plan of a village
- Double-peaked motif that might have figured a volcanic eruption
- Map, picture, picture map, both, neither?

![](images/chat-map.jpeg)

## _Saint-Bélec slab_ {data-background="#005c96" }

![](images/Saint-Belec-Slab.jpeg)

## _Saint-Bélec slab_ {data-background="#005c96" }

- c. 2150–1600 BCE
- Finistère, France
- Shows settlements, rivers, etc
- Surface carved to mimic land
- Possibly symbolic?

![](images/Finistere-Position.png)


##  _Tabula Peutingeriana_ {data-background="#005c96" }
![](images/TabulaPeutingeriana.jpeg)

## _Tabula Peutingeriana_ {data-background="#005c96" }
- Parchment copy ~ 1200 CE from Late Antiquity?
- 4th / 5th century CE original?
- Itineraries - distances between places
- What are your impressions of this?

![](images/roma-peut.jpeg)

## Frontispiece _Codex Mendoza_ {data-background="#005c96" }
![](images/codex.jpeg)


## Frontispiece _Codex Mendoza_ {data-background="#005c96" .smaller}

- c. 1541 CE, commissioned by viceroy of New Spain, Antonio de Mendoza
- Intended to record information about the Aztec empire
- Artist(s) were indigenous
- Images were often annotated in Spanish by a priest that spoke Nahuatl
- Schematic diagram of Tenochtitlan
	- Divided into four parts via canals
	- Mirrored the organization of the universe  
- Symbolic eagle and snake 
	- Lots of other symbols!
- Mix of different types of spaces / places - can you think of some?

## Marshall Islands Stick Charts {data-background="#005c96" }

![](images/stick-chart1.jpeg)

## Marshall Islands Stick Charts {data-background="#005c96" .smaller}
- Possibly for thousands of years
- Marshall Islands
- Curved sticks represented ocean swells
- Straight sticks represented the currents and waves around the islands
- Seashells represented the locations of the islands
- Memorized by navigators; unique to them

![](images/mislandmap.png)

## What is Spatial Analysis? {data-background="#005c96" }
- c. 1,400 years ago in Egypt - for land surveys
- Ancient Rome, *centuriation* for land alotments
- Practical reasons: Divide up the land!
![](images/rope_stretching.jpeg)

## Spatial Analysis {data-background="#005c96" }
- What do we think spatial analysis is now?

## Baron Pierre Charles Dupin {data-background="#005c96" }

::::{.columns}
:::{.column width="50%"}
![](images/Charles_Dupin.jpeg)
:::
:::{.column width="50%"}
- 6 October 1784 – 18 January 1873
- mathematician, engineer, economist, politician, mapmaker
- 1826 first *known* choropleth map, _Carte figurative de l'instruction populaire de la France, par Charles Dupin_
	- Shows availability of education
:::
::::

## Carte figurative de l'instruction populaire de la France  {data-background="#005c96" }
![](images/cp1.jpeg)

## Charles Picquet {data-background="#005c96" }
- French geographer and cartographer
- 1832, fighting Cholera in Paris
- Using shading to represent deaths in  _Rapport sur la marche et les effets du choléra-morbus dans ParisOffsite Link et les communes rurales du département de la Seine / par la commission nommée, avec l'approbation de M. le ministre du commerce et des travaux publics, par MM. les préfets de la Seine et de police ; année 1832_. 
- Spatial analysis!

##  {data-background="#005c96" }
![](images/cpmap.png)

## Jon Snow {data-background="#005c96" }

:::: {.columns}
::: {.column width="50%"}  
![](images/jon-snow.png)
:::
::: {.column width="50%"}  
- Earned his spot on the Night's Watch
- Fought white walkers
- Saved lots of people
- Worked for the Queen of the Seven Kingdoms
:::
::::

## John Snow {data-background="#005c96" }

:::: {.columns}
::: {.column width="50%"}
![](images/john-snow.jpeg)
:::
::: {.column width="50%"}
- Earned his MD
- Fought Cholera
- Saved lots of people
- Worked for the Queen of England
:::
::::


## Cholera Outbreak 1854 {data-background="#005c96" }
![](images/Snow-cholera-map-1.jpeg)

## Charles Joseph Minard {data-background="#005c96" }

:::: {.columns}
::: {.column width="50%"}
![](images/Charles_Joseph_Minard.png)
:::
::: {.column width="50%"}
- 27 March 1781 – 24 October 1870
- French  civil engineer
- Flow maps, numerical data on geographic maps
- Created what some call the best statistical graph of all time, produced in 1869
:::
::::

## _Carte figurative des pertes successives en hommes de l'Armée Française dans la campagne de Russie 1812–1813_ {data-background="#005c96" }

![](images/minard.png)


## Start of GIS {data-background="#005c96" }
:::: {.columns}
:::{.column width="50%"}
![](images/roger-tomlinson.jpeg)
:::
:::{.column width="50%"}
- Roger Tomlinson (with others!)
- Coined the term Geographic Information System
- His team created the first computerized GIS for Canadian government
- Idea: Traditional mylar sheets just did not cut it 
- Solution: Electronic layers of information
:::
::::

## What is a GIS? {data-background="#005c96" }


> A **geographic information system** (**GIS**) is a type of [database](https://en.wikipedia.org/wiki/Database "Database") containing [geographic data](https://en.wikipedia.org/wiki/Geographic_data_and_information "Geographic data and information") (that is, descriptions of phenomena for which location is relevant), combined with [software tools](https://en.wikipedia.org/wiki/Geographic_information_system_software "Geographic information system software") for managing, [analyzing](https://en.wikipedia.org/wiki/Spatial_analysis "Spatial analysis"), and [visualizing](https://en.wikipedia.org/wiki/Cartographic_design "Cartographic design") those data. <br/>
 
 -- Wikipedia, [*Geographic Information System*](https://en.wikipedia.org/wiki/Geographic_information_system)

## Different GIS tools  {.smaller auto-animate=true data-background="#005c96" background-image="../../images/CC_BY-SA_icon.svg" background-size=6% background-position="100% 100%"}

:::: {.columns}

::: {.column width="30%"} 

::: {data-id="columnhead1" style="background: #2780e3; padding: 10px;"}
Commercial
:::

- [ArcGIS (ESRI)](https://gisucla.maps.arcgis.com/home/index.html)
	- Industry leader
	- Entire ecosystem
	- ArcGIS Storymap
	- ArcGIS online
- Tableau
:::

::: {.column width="30%"}  

::: {data-id="columnhead2" style="background: #3fb618; padding: 10px;"}
Open Source
:::
-  QGIS  
- GRASS
- Omeka
- StoryMap JS
- Apache Superset
:::

::: {.column width="30%"}  

::: {data-id="columnhead3" style="background: #e83e8c; padding: 10px;"}
Other Tools  
:::

- Google Earth  
- Python  
- R
- Websites / WebGIS
:::

::::

## QGIS {auto-animate=true data-background="#005c96" }
![](images/qgis.svg){.absolute top=0 right=0 width="100" height="100"}
[https://www.qgis.org](https://www.qgis.org/en/site/)

>*A Free and Open Source Geographic Information System*

![](images/qgis-in-action.png){width="70%" height="70%"}

## QGIS{.smaller data-background="#005c96" background-image="../../images/CC_BY-SA_icon.svg" background-size=6% background-position="100% 100%"}
:::: {.columns}

::: {.column width="50%"}  

::: {data-id="columnhead2" style="background: #2780e3; padding: 10px; font-size: 1.75em"}
Capabilities
:::

- Free  
- Display, analyze, and edit spatial information  
- Create digital maps
- Supports common geospatial features  
- Supports different spatial file formats  
- Cross-platform  
:::

::: {.column width="50%"}

::: {data-id="columnhead2" style="background: #3fb618; padding: 10px; font-size: 1.75em"}
Drawbacks
:::

- No dedicated free support  
- Not "industry standard"
- Not part of the ESRI ecosystem
- Lacks some of the commercial tools and features
:::

::::

## Commonalities {auto-animate=true data-background="#005c96" }
- All GIS systems use GIS Data
- Need to project this data onto a representation of the Earth
- Concerned with geographic space
	- Food for thought: What about place?
- Not very great at representing time 

## GIS Data {auto-animate=true data-background="#005c96" background-image="../../images/CC_BY-SA_icon.svg" background-size=6% background-position="100% 100%"}
Data for GIS systems is primarily in two forms:

- Raster

- Vector


## Raster Overview {auto-animate=true data-background="#005c96" background-image="../../images/CC_BY-SA_icon.svg" background-size=6% background-position="100% 100%"}
:::: {.columns}

::: {.column width="50%"}  

::: {data-id="columnhead2" style="background: #2780e3; padding: 10px; font-size: 1.5em"}
Great For:
:::

- Large, continuous data sets  
- Terrain / Elevation  
- Images / Photographs
- Applications where *attribute* data is not extensive
- Where it is too computationally expensive to model the data
:::

::: {.column width="50%"}

::: {data-id="columnhead2" style="background: #3fb618; padding: 10px; font-size: 1.5em"}
Not so Great For:
:::

- Features (buildings, peaks, etc)
- Extensive attribute data
- Granular detail
- Querying for information

:::

::::

## {.smaller auto-animate=true data-background="#005c96" background-image="../../images/CC_BY-SA_icon.svg" background-size=6% background-position="100% 100%"}
::: {style="font-size: 2.5em; font-weight: 800"}  
Vector  
:::  

. . .

:::: {.columns}

::: {.column width="50%"}  
- Way to represent features
	- These can be anything that has a geospatial component
- Trace rivers, lakes, buildings, roads, add points, etc
	- X, Y, and sometimes Z axis
- Vertices and paths
	- Think of svg vs png files
- Points, lines, polygons 

:::

::: {.column width="50%"}
![](images/vector-over.png)

:::

::::


## Vector file formats{.smaller data-background="#005c96" background-image="../../images/CC_BY-SA_icon.svg" background-size=6% background-position="100% 100%"}

:::: {.columns}

::: {.column width="30%"} 
::: {data-id="columnhead1" style="background: #2780e3; padding: 10px;"}
Shapefile
:::

- Created by ESRI
	- Proprietary
- *De facto* industry standard
- Multiple files
- Limitations on attribute name size
- Spatially indexed
:::

::: {.column width="30%"}
::: {data-id="columnhead2" style="background: #3fb618; padding: 10px;"}
GeoJSON
:::

- Subset of the JSON format
- Human readable
- Designed for the web
- Essentially a text file
- No spatial index
- Can have slower performance
:::

::: {.column width="30%"}
::: {data-id="columnhead3" style="background: #e83e8c; padding: 10px;"}
GeoPackage
:::  

- New kid on the block
- Built on SQLlite (essentially a database file)
- Spatially indexed
- Faster performance
- Not as widely supported as the other formats
:::

::::

## {auto-animate=true data-background="#005c96"  .smaller}
::: {data-id="shapehead1" style="background: #2780e3; padding: 10px;"}
Shapefile
:::

| File Extension | Features|
|---|---|
| .shp (required)| feature geometry |
| .shx (required)| positional index |
| .dbf (required)| attribute information|
| .prj | projection description |
|  .sbn / .sbx | spatial index of the features |
| .fbn/.fbx | spatial index of read only features |
| .ain/.aih| attribute index |
| .ixs | geocoding index for read-write datasets | 
| .mxs | geocoding index for read-write OBD datasets| 
| .atx | differently formatted attribute index |
| .shp.xml | metadata in xml format|
| .cpg | specifies character encoding |
| .qix | alternative spatial index|


## {auto-animate=true data-background="#005c96" }

::: {data-id="geojsonhead2" style="background: #3fb618; padding: 10px;"}
GeoJSON
:::

```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [102.0, 0.5]
      },
      "properties": {
        "prop0": "value0"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "LineString",
        "coordinates": [
          [102.0, 0.0],
          [103.0, 1.0],
          [104.0, 0.0],
          [105.0, 1.0]
        ]
      },
      "properties": {
        "prop0": "value0",
        "prop1": 0.0
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [100.0, 0.0],
            [101.0, 0.0],
            [101.0, 1.0],
            [100.0, 1.0],
            [100.0, 0.0]
          ]
        ]
      },
      "properties": {
        "prop0": "value0",
        "prop1": { "this": "that" }
      }
    }
  ]
}
```


## {auto-animate=true data-background="#005c96" }
::: {data-id="packagehead3" style="background: #e83e8c; padding: 10px;"}
GeoPackage
:::  

![](images/geopackage-overview.png)

## CSV {auto-animate=true data-background="#005c96" }
- Comma-separated values
- Not inherently spatial or...well...anything
- Text file
- Spreadsheets!
- You will find a LOT of information in this format

## CSV {auto-animate=true data-background="#005c96" }
![](images/csv.png)
## Data {data-background="#005c96"}
![](images/data-star-trek.png)

## Where can I get data? {data-background="#005c96"}
- [Natural Earth](https://www.naturalearthdata.com/)
- [Ancient World Mapping Center GeoData](https://github.com/AWMC/geodata)
- [Los Angeles GeoHub](https://geohub.lacity.org/)
- [ArcGIS Living Atlas of the World](https://livingatlas.arcgis.com/en/home/)
- [OpenStreetMap](https://www.openstreetmap.org)

## Where can I get data? {data-background="#005c96"}

Exercise Time!

- [Million Dollar Hoods](https://milliondollarhoods.pre.ss.ucla.edu/)
