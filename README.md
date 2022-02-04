# Power-BI-Dashboards
My portfolio of Power BI Dashboards. Each folder contains the PowerBI Template file but also a static PDF report file as the template file will not work unless you have the specific excel sheets and credentials to access databases.

**CVYD Dashboard**
CBYD Dashboard displays information of Call Before You Dig Tickets (811) for the Municipality. E-tickets are provided from an e-mail server hosted by https://www.cbyd.com/ that are then inputted into an Excel sheet from a Python script in another repository (https://github.com/dcwalinski97/GIS-PythonScripts). The Dashboard then takes the information of tickets called in and uses it to display information about the 811 tickets in the town. Information such as data of tickets called, number of tickets called, progress of tickets called, and location of tickets called can all be explored. Data has been cleaned up in PowerQuery,

**Lining Dashboard**
Lining refers to the Trenchless Cured In-Place Epoxy Pipe Lining Process that is used to rehabilitate Old Sewer Pipe Lines. The Municipality has targeted "Old Borough" area which is Sewer Pipes that are over 100 years old and made from Clay and Tile material. This Dashboard tracks the lining of these pipes as well as the next phase which is Sewer Pipes installed before 1979 (when SDR35 PVC, a more durable product for gravity sewer, was used instead.) The Dashboard uses .JSON information from a ArcGIS hosted feature service. Lining values for pipes are updated as the Lining process continues for the Municipality.
