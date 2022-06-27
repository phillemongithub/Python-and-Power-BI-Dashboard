# Python-and-Power-BI-Dashboard


Python and Power BI Dashboard.

Requirements :

Python -Anaconda ( This will have a pytho wrapper that will be able to load the
pyhton libraries and create dataframes)

Power BI 


Steps:

To run your Python Script in Power BI Desktop:
In the Home ribbon, select Get data > Other.
Select Other > Python script as shown in the following image:


Select Connect. Your local latest installed Python version is selected as
 your Python engine. Copy your script into the Python script dialog box that appears. 
Here, we enter the simple Python script shown before.

copy this:

import pandas as pd
data =[["You",0],["Got",50],["it",100]]
df = pd.DataFrame(data, columns =["It","Works"], dtype=float)
print(df)


Select OK. If the script runs successfully, the Navigator appears and you can
load the data and use it. For the example, select df, as shown in the image, then Load.

Troubleshooting
If Python isn't installed or identified, a warning displays. You can also see a warning 
if you have multiple local machine installations. Revisit and review the previous Install Python
 and Enable Python scripting sections.

The you will see the data appearing on the Display options, 

You the continue with Power BI and creat your own Dashborad of your choice. 

Then Publish it. 


Published dashboard:

https://app.powerbi.com/groups/me/reports/2f1a0664-c7e7-4303-801f-6859b1418867/ReportSection


