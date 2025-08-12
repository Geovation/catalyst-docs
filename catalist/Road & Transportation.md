---
title: Road & Transportation
has_children: false
parent: Catalist
nav_order: 11
---

# Road & Transportation

| Name                                                                                            | Licensing | Data link                                                                                                                                                                                 | Docs link                                                                                     |
| ----------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [Overture Maps Foundation - Transporting Layer](#overture-maps-foundation---transporting-layer) | Open      | [Data link](https://docs.overturemaps.org/getting-data/)                                                                                                                                  | [Docs link](https://docs.overturemaps.org/guides/transportation/)                             |
| [Ordnance Survey NGD Transport](#ordnance-survey-ngd-transport)                                 | Premium   | [Data link](https://osdatahub.os.uk/)                                                                                                                                                     | [Docs link](https://docs.os.uk/osngd/data-structure/transport)                                |
| [Network Rail Data Feeds](#network-rail-data-feeds)                                             | Open      | [Data link](https://www.rspaccreditation.org/publicDocumentation.php#RSPS5xxx)                                                                                                            | [Docs link](https://publicdatafeeds.networkrail.co.uk/ntrod/account/profile)                  |
| [Road Collisions](#road-collisions)                                                             | Open      | [Data link 1](https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data), [Data link 2](https://cran.r-project.org/web/packages/stats19/index.html) | [Docs link](https://www.gov.uk/guidance/road-accident-and-safety-statistics-guidance)         |
| [Real-Time Location Estimates](#real-time-location-estimates)                                   | Premium   | [Data link](https://activeintelligence.bt.com/get-in-touch)                                                                                                                               | [Docs link](https://developer.bt.com/products/real-time-location-insights)                    |
| [Rail Insights](#rail-insights)                                                                 | Premium   | [Data link](https://activeintelligence.bt.com/get-in-touch)                                                                                                                               | [Docs link](https://developer.bt.com/products/rail-network-api)                               |
| [Bus Open Data Service](#bus-open-data-service)                                                 | Open      | [Data link](https://data.bus-data.dft.gov.uk/downloads/)                                                                                                                                  | [Docs link](https://data.bus-data.dft.gov.uk/guidance/requirements/)                          |
| [HERE Traffic Flow & Incidents](#here-traffic-flow-&-incidents)                                 | Premium   | [Data link](https://www.here.com/docs/bundle/traffic-api-v7-api-reference/page/index.html)                                                                                                | [Docs link](https://www.here.com/docs/bundle/traffic-api-developer-guide-v7/page/README.html) |

## Overture Maps Foundation - Transporting Layer

LineString and Point data representing transport nodes and links. Covers rail, road, water, and active travel. Data is sourced primarily from OpenStreetMap, and supplemented by TomTom.

- **Category:** Road & Transportation
- **Secondary Category:** 
- **Licensing:** Open
- **Data link:** [Data link](https://docs.overturemaps.org/getting-data/)
- **Docs link:** [Docs link](https://docs.overturemaps.org/guides/transportation/)



## Ordnance Survey NGD Transport

The OS NGD Transport Features Collection provides the most detailed topographic data available of the physical transport environment of Great Britain. The collection is made up of individual real-world topographic transport features, including roads, railway lines, tracks, and paths. Also includes streetlights.

- **Category:** Road & Transportation
- **Secondary Category:** 
- **Licensing:** Premium
- **Data link:** [Data link](https://osdatahub.os.uk/)
- **Docs link:** [Docs link](https://docs.os.uk/osngd/data-structure/transport)



## Network Rail Data Feeds

Real-time arrival and departure predictions, platform numbers, delay estimates, schedule changes and cancellations.

- **Category:** Road & Transportation
- **Secondary Category:** 
- **Licensing:** Open
- **Data link:** [Data link](https://www.rspaccreditation.org/publicDocumentation.php#RSPS5xxx)
- **Docs link:** [Docs link](https://publicdatafeeds.networkrail.co.uk/ntrod/account/profile)



## Road Collisions

Details about road collisions, including location, severity, date and time, and various details about the road and pedestrian infrastructure and conditions surrounding the incident. Two separate tables provide details about the casualties and vehicles respectively. Files are split by year, and can be accessed programmatically using an R Package

- **Category:** Road & Transportation
- **Secondary Category:** 
- **Licensing:** Open
- **Data link:** [Data link 1](https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data), [Data link 2](https://cran.r-project.org/web/packages/stats19/index.html)
- **Docs link:** [Docs link](https://www.gov.uk/guidance/road-accident-and-safety-statistics-guidance)



## Real-Time Location Estimates

Near-real-time population count estimates, broken down by age, gender, home & work, international visitors and percentage of the dwelling population compared to the moving population. Data updated every 15 minutes. Figures aggregated to H3 grid size 10 (each hex is ~1.5% of a square kilometer), or to LSOA. BT supplies related products for footfall to/from specific locations of interest. Other mobile network providers offer similar products:
O2 - https://www.o2.co.uk/business/solutions/mobile/data-mobile/o2-motion
Vodafone - https://developer.vodafone.com/api-catalogue/vodafone-analytics-realtime-footfall/overview

- **Category:** Demographics
- **Secondary Category:** Road & Transportation
- **Licensing:** Premium
- **Data link:** [Data link](https://activeintelligence.bt.com/get-in-touch)
- **Docs link:** [Docs link](https://developer.bt.com/products/real-time-location-insights)



## Rail Insights

Various insights into rail demographics and statistics: passenger volumes, station catchments, origin/destination, onboarders/alighters, rail-vs-road proportions.

- **Category:** Road & Transportation
- **Secondary Category:** Demographics
- **Licensing:** Premium
- **Data link:** [Data link](https://activeintelligence.bt.com/get-in-touch)
- **Docs link:** [Docs link](https://developer.bt.com/products/rail-network-api)



## Bus Open Data Service

Bus data updated every 14 hours including timetabling, routes, fares, and live location. Live location data is updated every 10 seconds. There is also limited disruption data, updated every minute, and coach data updated once a week. Data is supplied as XML.

- **Category:** Road & Transportation
- **Secondary Category:** 
- **Licensing:** Open
- **Data link:** [Data link](https://data.bus-data.dft.gov.uk/downloads/)
- **Docs link:** [Docs link](https://data.bus-data.dft.gov.uk/guidance/requirements/)



## HERE Traffic Flow & Incidents

Real-time traffic flow and incident data, compiled from various datasets including connected car probes, roadway sensors, and live operations centers. Flow/conjestion data is updated every minute and incident data every two minutes. Covers 70 country besides the UK. Flow/congestion data includes jam ratings, expected speed (with confidence ratings depending on data availability), jam tendancy (whether conjestion is increasing or decreasing junction closure), and sometime lane-specific information. Incident data is detailed and categorised with causes, times, criticality, junction transversability, and free-text descriptions. Restrictions are also included, including the vehicle type(s) and the restriction type (eg. emissions, weight, height, fuel type).

- **Category:** Road & Transportation
- **Secondary Category:** 
- **Licensing:** Premium
- **Data link:** [Data link](https://www.here.com/docs/bundle/traffic-api-v7-api-reference/page/index.html)
- **Docs link:** [Docs link](https://www.here.com/docs/bundle/traffic-api-developer-guide-v7/page/README.html)
