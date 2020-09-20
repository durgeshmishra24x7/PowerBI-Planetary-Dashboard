# PowerBI-Planetary-Dashboard
Fetch the Planetary Fact table from the NASA’s website, create an interactive PowerBI dashboard and apply an automatic dashboard refresh option.
Objective: - Fetch the Planetary Fact table from the NASA’s website, create an interactive PowerBI dashboard and enabled an automatic dashboard refresh option.

PowerBI brief introduction-
Power BI is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent, visually immersive, and interactive insights. Your data may be an Excel spreadsheet, or a collection of cloud-based and on-premises hybrid data warehouses. Power BI lets you easily connect to your data sources, visualize and discover what's important, and share that with anyone or everyone you want.

URL: -  https://nssdc.gsfc.nasa.gov/planetary/factsheet/

Steps need to perform: -
	Table Extraction
1.	Use python language to scrap the table and stored in a variable or in a data frame.
2.	Launch PowerBI Desktop application, Click on Get Data, search and click on Python script, click on connect and put the python script in the script window.
3.	Select the variable name where table result is stored.

	Dashboard Creation
1.	Create a Slicer button to make the dashboard responsive, Slicer will help to select and record the any details for any planet.
2.	Create graphs to explain the Diameter, Length of Days, Gravity and Mass by planet.
3.	Give a header name to the dashboard, like – Planetary Facts.
4.	Add few buttons on the graphs for dashboard further explanation.
5.	Use buttons like info, back etc. Create new page and add some graph.
6.	Add action as navigation pane to the buttons on the graph.
7.	In this dashboard, I created four new pages to show the Planet Rotation, Orbital Eccentricity, magnetic field.
8.	Create and add tooltips feature into the graph for advance response.
9.	Here, Count of moon graph is appended as tooltip feature in Diameter by Planets on NASA Facts page and Count of planets by magnetic field is appended on Moon page.
10.	Add background images to give realistic feel to the dashboard.
11.	Save and publish the dashboard on the PowerBI service.

Powered by Durgesh Mishra
