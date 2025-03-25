# Cartography
A collection of GIS maps created for university coursework, demonstrating proficiency in spatial analysis and cartographic design. Includes examples of hydrology, terrain, and least-cost-path modeling:

![lcp trails](https://github.com/avaerickson/Cartography/blob/main/Maps/lcp_trails.jpg?raw=true)
Least-cost-path analysis using landcover friction raster and digital elevation model (DEM) to map best routes for accessing pre-defined timber locations from a sawmill.


![hydro stream order](https://github.com/avaerickson/Cartography/blob/main/Maps/hydro_stream_order.jpg?raw=true)
Hydrology analysis using a conditional statement to isolate areas of high flow accumulation (DEM derrived) to predict stream locations. Visualizing stream order based on Strahler ordering system.

![viewshed guad peak](https://github.com/avaerickson/Cartography/blob/main/Maps/viewshed_guad_peak.jpg?raw=true)
Viewshed analysis using DEM informed line-of-sight algorithm to identify all areas visible from Guadalupe Peak.

![viewshed telecom](https://github.com/avaerickson/Cartography/blob/main/Maps/viewshed_telecom.jpg?raw=true)
Viewshed analysis using DEM informed line-of-sight algorithm to identify areas accessible by telecom signal, constrained by direction.

![hydro lcp](https://github.com/avaerickson/Cartography/blob/main/Maps/hydro_lcp.jpg?raw=true)
Combining least-cost-path and hydrology methods to use DEM derrived flow accumulation and flow direction rasters as inputs for least-cost-path computation to track the likely flow of a pollutant from a defined source.

![basin model](https://github.com/avaerickson/Cartography/blob/main/Maps/river_basin_model.png?raw=true)
Hydrology analysis using a conditional statement to isolate large water basins derrived from flow direction. 


![terrain resolution](https://github.com/avaerickson/Cartography/blob/main/Maps/terrain_resolution.jpg?raw=true)
Visualizing the impact of coarse vs. fine resolution on slope data, which can have terrain analysis implications. Resolution and slope relationship must be considered when selecting interpolaton methods during geoprocessing tasks. 


![terrain aspect](https://github.com/avaerickson/Cartography/blob/main/Maps/terrain_aspect.jpg?raw=true)
Terrain analysis using DEM to depict the direction each cell's slope is facing. 

![hydro regions](https://github.com/avaerickson/Cartography/blob/main/Maps/hydro_regions.jpg?raw=true)
Hydrology analysis defining connected regions of high flow accumulation and high wetness index, which reveals isolated areas where pollutants may spread quickly and easily (4-neighbor connectedness). 

![hydro dem](https://github.com/avaerickson/Cartography/blob/main/Maps/hydro_dem.jpg?raw=true)
Terrain and Hydrology analysis using DEM to create a hillshade to display flow accumulation, predicting location of streams. 

![accumulated cost](https://github.com/avaerickson/Cartography/blob/main/Maps/lcp_accumulated_cost.jpg?raw=true)
Least-cost-path analysis using landcover friction raster (accumulated cost raster) to determine, cell-by-cell, the easiest path from Origin to Destination. Contour lines visualize accumulated cost and cluster at areas of extremely high cost.
