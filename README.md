# QGIS-BiobasedPET

This repository contains information about the supply chain network for biobased PET production using a biobjective optimization model. The economic objective minimizes the total production costs and the environmental objective minimizes the environmental impact using different midpoint impact categories (*global warming potential - GWP, human toxicity potential - HTP, fossil depletion potential - FDP, and agriculture land occupation potential - ALOP*). 

For more information of the optimization model and assumptions, can be found in our publication - LINK PUBLICATION. 

## Included files

**Supply chain nodes layers** - These shapefiles include details of the different suppliers (biomass) and entities (bioethanol, ethylene, etc) of the supply chain such as plant ID, geographical location, company, total capacity).

1. [Biomass locations](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/Miscanthus_locations_availability.shp)
2. [Bioethanol plants](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/Bioethanol_plants_locations.shp)
3. [Ethylene plants](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/Ethylene_plants_locations_SHP.shp)
4. [MEG plants](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/EO_EG_plant_locations_shapefile.shp)
5. [Fast pyrolysis plants](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/fast_pyrolysis_locations.shp)
6. [PTA plants](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/PX_TPA_plant_locations.shp)
7. [PET plants](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/PET_plant_locations_shapefile.shp)
8. [Demand locations](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Locations/Demand_locations_shapefile.shp)

**Supply chain network layers** - These CSV data files contain the information of the origin and destination of the mass flows between supplier/entities. Additionally, the amount of mass transported between nodes is included in tonne/year. 

1. Supply chain network using GWP as environmental criterion [file](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Supply%20chain%20network/GWP_SC.xlsx)
2. Supply chain network using HTP as environmental criterion [file](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Supply%20chain%20network/HTP_SC.xlsx)
3. Supply chain network using FDP as environmental criterion [file](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Supply%20chain%20network/FDP_SC.xlsx)
4. Supply chain network using ALOP as environmental criterion [file](https://github.com/caaficus/QGIS-BiobasedPET/blob/main/Supply%20chain%20network/ALOP_SC.xlsx)






