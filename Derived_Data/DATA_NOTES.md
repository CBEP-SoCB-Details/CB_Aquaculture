# Derived GIS Data
All data contained here was derived from the statewide data on 
aquaculture leases contained in the "Original_Data" folder.
Here we provide a synopsis of Shapefile contents.  All
attributes are as in original files.  We have no original metadata 
on which to base descriptions of the attributes.  Thus we do not
provide our own interpretation of the meaning of data, to avoid
making mistakes that others may take as correct.

## 2015 Data
### CB_aquacult_poly_2015
### CB_aquacult_pts_2015
Selection from statewide data, restricted to locations within Casco Bay,
selected by hand.  Note that the 2015 data included point locations 
for both LPAs and leases in teh `aquacult_pts` data.

### Active_and_Emergency_CB_aquacult_poly_2015
### Active_and_Emergency_CB_Lease_pts_2015
### Active_and_Emergency_CB_LPA_pts_2015
Selections from the Casco Bay data, selecting only records for Active
and Emergency leases.  We split the point locations into separate shapefiles
for LPAs and full leases.

## 2017 Data
Most 2017 data was accessed directly from the source data, and reviewed
in ArcGIS by working with varous data subsets.  Consequently, there are 
fewer derived shapefiles for the 2017 data.

### AQ_LEASES_060717_Centroids
Most aquaculture leases are too small to show up well on maps at the 
scale of all of Casaco Bay.  It is convenient to show leases not as
polygons, but as points.  To produce this data layer, we converted the
statewide polygon data for aquaculture leases to a point layer, using 
ArcGIS's "Feature to Point" tool. This tool replaces feastures by 
their centroid, but retains all attributes. 

## 2019 Data
We did not conduct any analysis of the 2019 data, so there are no 
derived shapefiles from 2019.

## 2020 data
### aquaculture_centroids
As for the 2017 data, we converted polygon data on aquaculture leases
to point features using "Feature to Point".

### CB_aquaculture_centroids
### CB_LPA_centroids
Selection from statewide data, restricted to locations within Casco Bay,
selected by hand.

CB_active_aquaculture_centroids
CB_active_LPA_centroids
We selected only the currently "Active" leases and LPAs to produce 
draft maps of aquaculture activity in the Bay.

## Summary Numbers.xlsx
This contains a small table showing the number of active, emergency, 
pending, and terminated LPAs and leases shown in the data from 2015, 
2017, and 2021.  Note that DMRs conventions for showing related data
may have changed.  Where DMR statewide data contained no examples of
leases of LPAs in particular category, we marked that as "N/A" in the 
table.  The value "0" means there **were** examples of that combination
in the statewide data, but none in the Casco Bay region.

