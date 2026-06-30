# National-Parks
Description: 
This dataset lists all 63 U.S. National Parks, their primary visitor centers, and the nearest international airports, including geographic coordinates and estimated distances.  
The purpose of this project is to determine if a National Park's proximity to an international airport affects its attendance numbers.

Dataset Name: 
U.S. National Parks Visitor Centers and Nearest Airports 

Dataset structure:
A longitudinal panel dataset in tidy (long) format that combines monthly National Park visitation statistics with geographic and accessibility attributes for spatial, temporal, and tourism analysis.
This structure is highly suitable for:
- Correlation analysis (like your drive-time study)
- Regression modeling
- GIS integration
- Dashboard visualizations
- Data catalogs and API deployment.
  
Fact dataset: "Attendance"
Dimension/Support datasets: "Location", "Pivot Table"

License: 
CC0 1.0 Universal (Public Domain). 
This dataset is compiled from publicly available U.S. government sources (NPS, FAA, and open geographic data). 
No ownership is claimed over individual source data.  

Sources:  
- National Park Service (NPS)  
- Federal Aviation Administration (FAA)  
- Open geographic datasets  

Privacy:  
This dataset contains no personal or sensitive information.  

Security:  
Data is intended for informational and planning purposes only.  

Accessibility:  
- Plain-language column names  
- Decimal degree coordinates (WGS84)  
- Compatible with GIS and spreadsheet tools 

Notes:
- “Nearest international airport” is based on practical travel proximity, not just strict geodesic distance. 
- Some remote parks (especially Alaska) use the closest major airport with international capability, even if regional airstrips are closer. 
- Visitor centers selected are the primary or most commonly used entry points. 
