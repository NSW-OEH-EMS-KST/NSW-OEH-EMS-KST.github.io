### Welcome to the KST GitHub Pages


[Grid Garage | ](#grid-garage)
[KST Custom Tools | ](#kst-custom-tools)
[Aboriginal Site Decision Support Tools | ](#ASDST)
[Contact](#support-contact)

****

## <a name="grid-garage"></a> Grid Garage

The **Grid Garage** Toolbox is designed to help you undertake the Geographic Information System (GIS) tasks required to process GIS data (geodata) into a standard, spatially aligned format.  This format is required by most, grid or raster, spatial modelling tools such as the [Multi-criteria Analysis Shell for Spatial Decision Support (MCAS-S)](http://www.agriculture.gov.au/abares/aclump/multi-criteria-analysis). Grid Garage contains 36 tools designed to save you time by batch processing repetitive GIS tasks as well diagnosing problems with data and capturing a record of processing step and any errors encountered.

Grid Garage provides tools that function using a list based approach to batch processing where both inputs and outputs are specified in tables to enable selective batch processing and detailed result reporting. In many cases the tools simply extend the functionality of standard ArcGIS tools, providing some or all of the inputs required by these tools via the input table to enable batch processing on a 'per item' basis. This approach differs slightly from normal batch processing in ArcGIS, instead of manually selecting single items or a folder on which to apply a tool or model you provide a table listing target datasets. In summary the
Grid Garage allows you to:

* List, describe and manage very large volumes of geodata.
* Batch process repetitive GIS tasks such as managing (renaming, describing etc.) or processing (clipping, resampling, reprojecting etc.) many geodata inputs such as time-series geodata derived from satellite imagery or climate models.
* Record any errors when batch processing and diagnose errors by interrogating the input geodata that failed.
* Develop your own models in ArcGIS ModelBuilder that allow you to automate any GIS workflow utilising one or more of the Grid Garage tools that can process an unlimited number of inputs.
* Automate the process of generating MCAS-S TIP metadata files for any number of input raster datasets.

The Grid Garage is intended for use by anyone with an understanding of GIS principles and an intermediate to advanced level of GIS skills.  Using the Grid Garage tools in ArcGIS ModelBuilder requires skills in the use of the ArcGIS ModelBuilder tool.

**Download Instructions:** Create a new folder on your computer or network and then download and unzip the zip file from the GitHub Release page for each of the following three items. There is a folder in each zip file that contains all the files. See the Grid Garage User Guide for instructions on how to install and use the Grid Garage Toolbox with the sample data provided. 

| Files | Link  | Notes |
| --- | --- | --- |
| Grid Garage ArcGIS Toolbox | [Grid Garage v3.1.0 Release](https://github.com/NSW-OEH-EMS-KST/grid-garage/releases/tag/grid_garage_3.1.0)| Version 3.1 introduced the Metadata tools that can by used to generage MCAS-S TIP files. |
| The Grid Garage User Guide | [See the Grid Garage Wiki for the user guide](https://github.com/NSW-OEH-EMS-KST/grid-garage/wiki) |The user guide is now online. |
| The Sample Data for use in tutorials | [Sample Data v1.0.2 Release](https://github.com/NSW-OEH-EMS-KST/grid-garage-sample-data/releases) | |

****

## <a name="kst-custom-tools"></a> KST Custom Tools 

**KST Custom Tools** is a python toolbox with a few custom ArcGIS tools developed by the NSW OEH Ecosystem Management Science Knowledge Services Team.

These tools address analysis situations where there is no easy or obvious workflow within ArcGIS was available.

The tools can be downloaded here: 
[KST Custom Tools Releases](https://github.com/NSW-OEH-EMS-KST/kst-custom-tools/releases)


****

## <a name="ASDST"></a> Aboriginal Site Decision Support Tools (ASDST)

The **ASDST** tools are for in-house work on projects affecting Aboriginal sites. The tools require access to specific datasets.

Releases can be found here: [ASDST Releases](https://github.com/NSW-OEH-EMS-KST/asdst/releases)


****

## <a name="support-contact"></a> Support or Contact

Having trouble with our products?

Email: tom.barrett@environment.nsw.gov.au

****

All Grid Garage, KST Custom Tools and Aboriginal Site Decision Support Tools (ASDST) tools, Python scripts and associated documentation are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](http://creativecommons.org/licenses/by/4.0/deed.en). The legal code for the license is available at [Creative Commons](http://creativecommons.org/licenses/by/4.0/legalcode).  OEH does not represent or warrant that calculations in Grid Garage, KST Custom Tools and Aboriginal Site Decision Support ArcGIS Toolboxes are accurate, correct, useful or meaningful, and does not accept any responsibility for the use of these tools in either the form as supplied or as modified by others.

**© New South Wales Office of Environment and Heritage (OEH), 2016.**

****
