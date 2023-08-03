# Orion Constellation Star Mapping

**Python, Jupyter Notebook, Excel, Matplotlib, Axes3D, Plotly**

**Main goal:** Using Python and Jupyter Notebook to create a 3-dimensional representation of the principal stars in the Orion constellation. By importing matploblib and especially the Axes3D module, the goal is to make an accurate IRW representation of the stars. The star data from the first project comes from Codecademy. The star data from the second Supplement is open-sourced from the internet for astronomical right ascension, declination, and distances, and then converted and normalized using an Excel file/ .csv to generate a new set of (x,y,z) coordinates to use for plotting. The Supplement file can thus be used to generate a 3-D representation of any group of stars given sky coordinates and distances. The format of the first project comes from Codecademy, but with edits to the data for an improved presentation.

**Preprocessing:** Preprocessing primarily applies to the Supplement. As noted above, astronomical data i.e. right ascension, declination, and distance measurements were open-sourced from the internet and then were processed by a custom-written Excel program to generate the correct (x,y,z) coordinates for display by Axes3D. This custom program can then be extended for use on any set of stars given the initial astronomical coordinates.

**Modules:** The primary modules used are matplotlib and Axes3D.

**Conclusions:** With Axes3D and the custom processing program, any group of stars can be shown in a true orientation that demonstrates the actual relationship among the sample of stars. For examples, the four primary stars of Betelgeuse, Bellatrix, Rigel, and Saiph are all visualized to be much closer to earth than the belt and other stars. Effective visualization is crucial for data analysts and scientists.

- Code: Python, Jupyter Notebook, Excel
- Packages: Matplotlib, Axes3D, Pandas, Numpy, Plotly
- Data Source: Initial raw data for this project data provided by Codecademy, and additional data researched and open-sourced from the internet.
  
![newplot](/newplot.png)
