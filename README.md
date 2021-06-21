_your zenodo badge here_

# nelson_etal_2021_scidata

**An open-source geospatial data package for determining renewable and non-renewable power plant siting suitability across the United States**

Kristian D. Nelson<sup>1\*</sup>, Chris R. Vernon<sup>1</sup>, Jennie S. Rice<sup>1</sup>, Kendall Mongird<sup>1</sup>

<sup>1 </sup> Pacific Northwest National Laboratory, Richland, WA. 99354

\* corresponding author:  kristian.nelson@pnnl.gov

## Abstract
Determining suitable land areas to accommodate future electricity system expansion requires a multitude of geospatial datasets to be able to address a wide range of power plant siting opportunities and constraints. These datasets encompass a variety of sectors, scales, and formats, posing a significant data fusion challenge.  This data descriptor describes the process of discovery, harvesting, documenting, archiving, and quality controlling a collection of geospatial datasets used for renewable and non-renewable power plant siting. This accumulation of datasets will be used in the Capacity Expansion Regional Feasibility Model (CERF) as inputs. CERF uses these data to determine feasible and cost-effective siting options for utility-scale renewable and non-renewable power plants within the contiguous United States at a 1 km resolution. This unique open-source data package facilitates defining both common and technology-specific areas where power plants may be sited and enables other researchers to include their own data in the same common format.

## Journal reference
TBD

## Code reference
Cite version 2 of CERF

## Data reference

### Input data
Reference for each minted data source for your input data.  For example:

Human, I.M. (2021). My input dataset name [Data set]. DataHub. https://doi.org/some-doi-number

### Output data
Reference for each minted data source for your output data.  For example:

Human, I.M. (2021). My output dataset name [Data set]. DataHub. https://doi.org/some-doi-number

## Reproduce my experiment
Fill in detailed info here or link to other documentation that is a thorough walkthrough of how to use what is in this repository to reproduce your experiment.


1. Install the software components required to conduct the experiement from [Contributing modeling software](#contributing-modeling-software)

2. Download and install the supporting input data required to conduct the experiement from [Input data](#input-data)

3. Run the following scripts in the `workflow` directory to re-create this experiment:

| Script Name | Description | How to Run |
| --- | --- | --- |
| `step_one.py` | Script to run the first part of my experiment | `python3 step_one.py -f /path/to/inputdata/file_one.csv` |
| `step_two.py` | Script to run the last part of my experiment | `python3 step_two.py -o /path/to/my/outputdir` |

4. Download and unzip the output data from my experiment [Output data](#output-data)

5. Run the following scripts in the `workflow` directory to compare my outputs to those from the publication

| Script Name | Description | How to Run |
| --- | --- | --- |
| `compare.py` | Script to compare my outputs to the original | `python3 compare.py --orig /path/to/original/data.csv --new /path/to/new/data.csv` |

## Reproduce my figures
Use the scripts found in the `figures` directory to reproduce the figures used in this publication.

| Script Name | Description | How to Run |
| --- | --- | --- |
| `generate_figures.py` | Script to generate my figures | `python3 generate_figures.py -i /path/to/inputs -o /path/to/outuptdir` |
