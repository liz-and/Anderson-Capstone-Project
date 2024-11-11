Data files explanation:

Moose_Plot_Data.csv --> Has data on each plot area. 

Columns are:
- plot = the unique plot identification number

- browse_index = sum of proportion of browsed stems and total stems browsed/2

- lat = latitude

- elev_m = elevation (meters)

- dist_h2o_m = distance (meters) from the plot to the nearest wetland or water body

- hilltop = is the plot located on a hilltop (0 = no, 1 = yes)

- swamp = is the plot located in a swamp (area with saturated soil and wetland plant indicators) (0 = no, 1 = yes)

- wetland_forest = is the plot located in a swamp or floodplain forest (0 = no, 1 = yes)

- tall_shrubs = the density of shrub stems that are over 1.8m high in the 200m² area surveyed

- dist_conifer_m = distance (meters) to the nearest patch of conifer forest 

- hemlock_ba = relative % of basal area of hemlock in the plot

- sugar_maple_ba = relative % of basal area of sugar maple in the plot

- red_maple_ba = relative % of basal area of red maple in the plot

- spruce_fir_ba = relative % of basal area of spruce and fir combined in the plot

- oak_ba = relative % of basal area of all oak species in the plot

- white_pine_ba = relative % of basal area of white pine in the plot

- harvest_intensity_m2/ha = amount of basal area removed from a harvested stand (m²/ha)

- watershed = the watershed forest where the plot was located. 0 is Quabbin Forest, 1 is Ware River Forest

- deer_density = estimated number of deer per km² in the area the plot was located

- harvest = harvest status of the plot. 0 is the plot was located in an unharvested stand, 1 is the plot was located in a harvested area

- dist_dev_m = distance (meters) from the plot to the nearest developed area (developed area defined by MassGIS). Distances greater than 1000m were assigned a value of 1000. 




Moose_Tree_Data.csv --> has data on each tree that was surveyed. 

Columns are: 
- plot = the unique plot identification number

- species = the tree species or genus name

- dbh_cm = diameter at breast height (cm) of the tree. Seedlings under 2.5cm assigned NA

- count = the number of stems on the tree

- browsed = whether the tree was browsed at the height of above 1.8meters and below 3meters. 0 is unbrowsed, 1 is browsed, NA is no stems were within the available browse range or the browse status was inconclusive so the stem was not assessed.

- stripped = whether the tree was stripped at the height of above 1.8meters and below 3meters. 0 is stem bark not stripped, 1 is stem bark stripped.

- broken = whether the tree was broken at the height of above 1.8meters and below 3meters. 0 is stem not broken by moose, 1 is stem broken by moose. 