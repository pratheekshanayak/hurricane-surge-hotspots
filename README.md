### Identifying hotspots of vulnerability during hurricane storm-surge inundation

Storm surges during hurricanes can cause significant flooding in coastal and inland regions resulting in damage to property and loss of life. 
Identifying regions that are most vulnerable to such damage is essential for improving disaster response and building community resilience. 
Providing timely and crucial information can also help citizens access necessary resources for their safety and well-being.

A comprehensive two-part analysis is conducted to understand the impact of storm-surge inundation:
1. For Planners / Government Agencies: The first part focuses on providing spatial information for planners and government agencies. 
The data mapped includes key demographic, economic and housing characteristics. Choropleth maps are used to visually depict the distribution 
of populations affected by storm surges across various census tracts of Washington, DC along with other attributes.  These visualizations 
are designed to help decision-makers prioritize resources and tailor their response strategies for different categories of storms, thus 
enabling a more effective, data-driven approach to disaster preparedness and mitigation.

2. For Citizens: The second part adopts a citizen-centric approach to empower individuals with actionable information in the event of a storm. 
By allowing users to input a specific point location, the analysis identifies the category of storm that would affect that area, the pharmacies 
within a one-mile radius, highlighting those that would be inundated by storm surge waters. This information can be vital for individuals needing 
access to essential services like pharmacies during emergencies.


### Data: 

Source - Open Data DC portal ((https://opendata.dc.gov/)).

- Storm surge risk areas(category-wise) in DC: Shapefiles that give areas in DC that are at risk of inundation for different categories of storms. 
- ACS 5-year data for DC census tracts: Shapefiles of census data that include information on population, housing, income etc. within each census tract in DC. 
3 categories of data were used: Demographic, Economic, Housing.
- Pharmacy locations in DC: Shapefile with locations of licensed pharmacies in DC.


1. `Planners_Part1.ipynb` - Includes data cleaning, analysis and visualization based on user-inputs for Part 1. Choropleth maps are used understand spatial 
distribution of attributes across DC census tracts. Overall impact for different categories of storms are assessed.
2. `Citizens_Part2.ipynb` - Uses input for a specific point location and identifies the category of storm that would affect that area. Also shows the pharmacies 
within a one-mile radius, highlighting those that would be inundated by storm surge waters.

`Data/` contains surge areas, ACS and pharmacy locations data obtained from [Open Data DC portal](https://opendata.dc.gov/).

`Report.pdf` gives a brief overview of the datasets, methodology and results.
