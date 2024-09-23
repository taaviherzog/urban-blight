# Visualizing Geographical Clustering of Adversity and Affluence in Pittsburgh
This is a project I've been working on in collaboration with professors in the Pitt Business Analytics program, as well as with external stakeholders including Department of Inspections experts. Adversity is measured as the frequency of fires, crimes, and property code violations. Affluence is measured as the average value of surrounding home sales prices. As anticipated, certain areas of the city are high in one and low in the other, although there are some neighborhoods that are the same in both categories. For example, Downtown is both high in Adversity as well as in Affluence. (Files containing the processed dataset and output images and are contained in the repository)

The project involved three main stages:
 - **Data Retrieval:** This is done via API calls to the Western Pennsylvania Regional Data Center
 - **Data Engineering:** This requires relating multiple datasets via parcel IDs and gocoded coordinates. This is the most extensive step, and makes use of the GeoPandas and Polgyon libraries
 - **Visualization:** This is the final output, providing a visual contrast between Adversity and Affluence for various pockets around the city

This project required that I learn about representing data geospatially.
