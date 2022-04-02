![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P1.png)
# Module 13  Mapping Earthquakes
### by Terra Lasho 

## Summary: 

### For this Project, I was tasked to develop an interactive map portraying the most recent earthquakes relative to magnitude and relation to tectonic plates using JavaScript, Leaflet.js, and geoJSON data libraries.  I was also tasked to include overlays depicting different map visuals and a clickable option to add or remove earthquakes, earthquakes with a magnitude of >4.5, and tectonic plate locations.
--------------------------------------------------------------------------------------------------------------
## Deliverable 1: Add Tectonic Plate Data

### For the first part of this Deliverable, I added layer groups for all earthquakes, tectonic plates, and major earthquakes (deliverable 2). I then labeled them for the overlay legend.

![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P2.png)

### For the next part of this Deliverable, I passed the tectonic plate data to the geoJSON() layer, adding color and width to the graphic, as well as adding the group variable to the map.

![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P3.png)


---------------------------------------------------------------------------------------------
## Deliverable 2: Add Major Earthquake Data

### For the first part of this Deliverable, I added a major earthquake layer group for this data.  I next added this to the overlay legend.  I then used d3.json() to extract major earthquake data from the GeoJSON Summary Feed (>4.5 magnitude for the last seven days). I then format/styled this as the same as the normal earthquake data.  I then changed the color to depict the various Earthquake Magnitudes.
![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P4.png)
### For the next part of this Deliverable, I changed the radius of the circle marker to depict the radius of the earthquake. I then incorporated the major earthquake data into the GeoJSON layer and made the circular markers, created a popup for each circle displaying the magnitude and location of the earthquake, and added the major earthquake variable to the map.
![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P5.png)
![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P6.png)
![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P7.png)
![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P8.png)
---------------------------------------------------------------------------------------------
## Deliverable 3: Add an Additional Map

### For this Deliverable, I added another map (dark-version) using leaflet.  I added the overlay option to the map, and made sure all of the earthquake and tectonic data were visible.
![]( https://github.com/Beetleee/Mapping_Earthquakes/blob/main/Resources/P9.png)

