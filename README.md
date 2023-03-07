<h1 align="center">
  SEEK Australia Job Listing
</h1>

**Project Description**: This is a dashboard made with Tableau with content about recruitment statistics posted on SEEK - one of the largest employment marketplace sites in Australia. Using Tableau allows users to spend less time creating graphs and images. Besides, Tableau uses algorithms to intelligently understand and format data-based charts, handling most of the heavy lifting and complexities in data analysis. Dataset is open data collected from [here](https://data.world/promptcloud/30000-job-postings-from-seek-australia). To get the right data, the first step is to preprocess the raw data, which is done in Python code. One limitation in this personal project is that it is not yet published on Tableau Public for everyone to use, but this will be fixed soon in the future.

<h4 align="center">The project is made by Phuc An Nguyen</h4>

<img src="Tableau Dashboard.png"
     style="float: left; margin-right: 10px;" />

## Key Features

* State and City filter (single selection) with Apply and Reset button
  - All graph and information change base on state and city
* Category, Job Type and Post Date filter (multiple selection)
  - All graph and information change base on filters 
* Graph hover and tooltip in Map
* Download image

## How to Install and Run the Project
* Method 1: Run the directly `Tableau_project.twb` file on Tableau to see the results

* Method 2: Rerun from the original file
  - Run file `Tableau_Project_Preprocessing.ipynb` on Jupyter notebook to preprocess 2 raw data files and output file `seek.csv` 
  - Run the file `Tableau Project.twb` on Tableau to see the results

## How To Use
- Default will show all - means the chart will show all data
- Can move the mouse around the charts, click on details to view as well as sort
- Select the State and City you want to see details, chick Apply button to see the results, if you want to return to the default state, press Reset button
- Select the category you want to view with multiple selection, the charts and metrics will change based on your filter. Similar to Job Type and Post Date
- Click Download Image button to download the dashboard as an image

> **Note**
> Reset button only applies to State and City filters

## Credits
This software uses the following open source packages:

- [Jupyter Notebook](https://jupyter.org/)
- [Tableau Desktop](https://www.tableau.com/products/desktop)
