# Water-yield-change-(GIS project)
The Intergovernmental Panel on Climate Change (IPCC) in his sixth evaluation round, posits that it is certain that temperatures have increased during the twentieth century. This increase in temperature linked to climate change will have various consequences, such as extreme heat waves in many countries, the increase of intense precipitation and the risk of intense drought events. For this study, we use Representative Concentration Pathways (RCP) scenarios 4.5, 6.0 and 8.5 to conduct a spatial analysis of the evolution of water yield in the autonomous communities of La Rioja, Aragón and Catalunya (Ebro basin), as compared to the present.

This research has been made in collaboration with Anja Hajdukovic, Athénais Navarro, Caroline Steinfeld and Lina Roriguez as part of a group project at the University of Geneva.

Methodology:

Getting 6 different types of data:
- Ebro basin region
- Total annual precipitation
- Average annual reference evapotranspiration
- Plant available water content and root restricting layer depth
- Land use, land cover
- Watershed and subwatershed

The water yields change estimations for the 3 future scenarios requires to run the inVEST package. For this, it is necessary to pre-process the layers (e.g. reproject ESPG 3042 to 4326, clip by mask layer).
