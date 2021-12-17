# CB_Aquaculture
Geospatial data on Aquaculture Leases and "Limited Purpose Aquaculture" 
permits in Casco Bay, from 2015, 2017, 1nd 2020.

This is principally a GIS data archive.  The combination of recent and 
older versions of Maine DMR aquaculture licenses and permits data, 
allows assessment and documentation of changes in locations and
numbers over time.

All GIS data was downloaded from Maine DMR sources, but exact URLs and 
dates of access vary, as DMR has made the data available in different 
forms over the years.  In particular, the 2015-era data is in a different 
format than later downloads.

DMR does not provide complete metadata for these files, so some 
interpretation of attributes is required.  We interpret key attributes
as follows:

The "Status" attribute has taken on Four values in recent years, "A" 
for Active, "P" for Pending, and "T" for Terminated. Value "E", for 
Emergency.  

Emergency leases are temporary sites, explained on the DMR 
Aquaculture [webpage](https://www.maine.gov/dmr/aquaculture/forms/index.html)
as follows:

> For existing shellfish lease holders the Department has the authority 
  to issue an emergency lease to allow shellfish stock to be moved temporarily 
  off an existing lease when the health and safety of the shellfish are 
  threatened.

They are authorized for only six months at a time.Emergency leases were 
abundant in the 2015 LPA data, but are absent in the data on
Casco Bay we accessed in 2017 and 2020.  

For counting up active aquaculture operations, we treated "Emergency" leases
 as "Active" in 2015.

The "LeaseType" attribute has taken on four values:
"L" for a "Limited Purpose Aquaculture" license or LPA, "E" for
Experimental, "S" for Standard and "F" for Finfish.  
