# powerbi-project-cgi

## Visualizations: Power BI Storytelling 

## Project Resources

[Kanban Board](https://trello.com/b/adgvaQzY/powebi-project)

## About the project

![about](about.png)

## Steps

- [ ] Find a data set that seems interesting to you online. Here are some good websites to get datasets from:
  - https://archive.ics.uci.edu/ml/datasets.php
  - https://www.kaggle.com/
  - https://data.world/
- [ ] Load the data into Power BI Desktop.
- [ ] Use Power Query Editor and/or other tools from within Power BI Desktop to clean and transform your data so it is ready for analysis.
- [ ] Use the Modeling View in Power BI to build a data model.
- [ ] Build out visualizations in the same Power BI Desktop (`.pbix` file) using this data.
- [ ] Focus on the story you are telling with the visualizations you decide to use.
- [ ] Create a new workspace in Power BI Service. 
- [ ] You can choose what to name this workspace (e.g., “CAP Mini Project Practice”).
- [ ] When you create the workspace, open the Advanced settings and select “Premium per user” under license mode.
- [ ] Publish the `.pbix` file with your modeled data and visualizations to this new workspace.
- [ ] Once you have published the `.pbix` file, open a blank report in Report Builder. 
- [ ] Add a data source connecting to the Power BI dataset in the workspace you just published the`.pbix` file to.
- [ ] Add a dataset to retrieve data from the data source you just created.
- [ ] You should retrieve any data that will be needed for the report
- [ ]  You will also likely need to create separate datasets to retrieve the data necessary for setting up report parameters.
- [ ]  Define report parameters and design the report to meet the requirements specified in the Deliverables section.
- [ ]  Once you have designed and tested the report, publish the paginated report (`.rdl` file) to the Power BI Service to the same workspace with your `.pbix` file and `.rdl` file to test it.
- [ ]  Republish your `.pbix` file (with the report and dataset) and `.rdl` file to the same workspace as you iteratively develop them.
- [ ]  Once you are done developing, first publish the `.pbix` file to the `CAP Training 5/22 - Mini Projects` workspace with the naming convention `“FNameLName_DE4”`.
- [ ]  **After publishing your interactive report to the `CAP Training 5/22 - Mini Projects` Workspace, open your `.rdl` file and create a new data source connecting the Power BI dataset that was published to the `CAP Training 5/22 Mini Projects` workspace.**
- [ ]  You can delete the old data source after successfully connecting to the new data source.
- [ ]  After creating the new data source, change the data source for all datasets in your report (`.rdl` file) to this new data source.
- [ ]  Run the report locally in the Report Builder application to ensure you were able to connect to the data source and dataset(s) successfully.
- [ ]  If the data appears as expected, publish the `.rdl` file to the `CAP Training 5/22 - Mini Projects` Workspace with the naming convention `“FNameLName_DE4”`.
- [ ]  Test that Report and Paginated Report look as expected in the workspace. **It is especially important that every time you publish a paginated report or an interactive report that you run it in the Power BI Service to ensure it renders properly and there are no errors.**

*Note*: If you need to delete and republish your dataset/interactive report for any reason, then ensure you follow the steps above to create a new data source connecting to the shared dataset in the CAP Training 5/2022 - Mini Projects workspace and change the data source for each of the data sets in your .rdl file.


### Helpful hint #1:

- You will need to create additional datasets to populate the available values for the parameters you want to add to your report (E.g., if you wanted a parameter for year, so that the user can filter the data on the report by year, then you would need to create another Power BI dataset that retrieves the data for years.
- To do this, you would create a table in Power BI Desktop with the “Year” field and then use the performance analyzer to copy the DAX query).

### Helpful hint #2: 

- Parameters do not automatically filter the data in your dataset once they are created.
- Think of the parameter selection as a stored value. You must then use that stored value (the parameter value the user selects) in a filter condition to filter the data in your dataset. 
  - So, first create the parameter
  -  Then, add a filter on the your main dataset to filter the data.


## Plan

## Deliverables

### [ ] Dataset

### [ ] Report

- [ ] `.pbix` file published to `the CAP Training 5/22 - Mini Projects workspace`
- [ ]  At least 2 pages
- [ ]  Button or bookmark to navigate between them
- [ ]  Tabs named intuitively
- [ ]  Title on every sheet
- [ ]  Minimum 4 different types of visuals
- [ ]  At least one slicer (synced across pages)
- [ ]  At least one measure using DAX
- [ ]  Cohesive styling/theme across sheets (fonts, colors, etc.)
- [ ]  Optional branding (does not have to be CGI branding, but if it is, please use color/typography/logos recommended in [CGI Branding Guidelines](https://brand.cgi.com/site/login)).

### [ ] Paginated Report

- [ ] `.rdl` file published to `the CAP Training 5/22 - Mini Projects workspace`
- [ ] At least 2 parameters
- [ ] Cohesive styling with the Desktop Report (does not need to be heavily stylized, but at least the same fonts and consistent branding)
- [ ] Report must maintain `rdl` formatting when exported to `pdf` (no new page jumps, extended tables, etc.)
  
You will also at some point be asked to demo and talk us through your reports. There are resources linked in the CAP Power BI Training PowerPoint deck and the MS PBI Report Builder Resources List (both are shared in the Data Engineering Training teams channel). Specific requirements are below:

## Steps to Reproduce the project
