This is the first group project for DIVOC-91 and MSU's AI Bootcamp! 
Team Members:  Chris, Taylor, Isaac, and Tom 

Hi Team, 
Per our discussion, here's an explanation of the files that I uploaded to our repo.  Please do a pull to your cloned repo, 
then copy the notebooks and the Resources folder to a separate folder to run the notebooks and further analyze the data. 
This will keep our repo folder clean until you have something that you want to push to it. 

**Notebooks:** 
- **create_2021_analysis_data_file.ipynb** - Reads 2021 Household Pulse Survey files to creates the **pulse2021_survey_data.csv** file 
- **create_2022_analysis_data_file.ipynb** - Reads 2022 Household Pulse Survey files to creates the **pulse2022_survey_data.csv** file 
- **create_2023_analysis_data_file.ipynb** - Reads 2023 Household Pulse Survey files to creates the **pulse2023_survey_data.csv** file 
- **covid_analysis_plots.ipynb** - Reads 2021-2023 pulse survey data files and plots **COVID vs. Anixous, Worry, Interest, and Down** responses 

**Data Files in the Resources folder:** 

- **2021 data:** 
    - **pulse2021_puf_24.csv** - 2021 1Q US Census Bureau Household Pulse Survey file (survey period: 2/3/2021-2/15/2021) 
    - **pulse2021_puf_29.csv** - 2021 2Q US Census Bureau Household Pulse Survey file (survey period: 4/28/2021-5/10/2021) 
    - **pulse2021_puf_38.csv** - 2021 3Q US Census Bureau Household Pulse Survey file (survey period: 9/15/2021-9/27/2021) 
    - **pulse2021_puf_39.csv** - 2021 4Q US Census Bureau Household Pulse Survey file (survey period: 9/29/2021-10/11/2021) 

- **2022 data:** 
    - **pulse2022_puf_42.csv** - 2022 1Q US Census Bureau Household Pulse Survey file (survey period: 1/26/2022-2/7/2022) 
    - **pulse2022_puf_45.csv** - 2022 2Q US Census Bureau Household Pulse Survey file (survey period: 4/27/2022-5/9/2022) 
    - **pulse2022_puf_48.csv** - 2022 3Q US Census Bureau Household Pulse Survey file (survey period: 7/27/2022-8/8/2022) 
    - **pulse2022_puf_52.csv** - 2022 4Q US Census Bureau Household Pulse Survey file (survery period: 12/9/2022-12/19/2022) 

- **2023 data:** 
    - **pulse2023_puf_55_2023_1Q.csv** - 2023 1Q US Census Bureau Household Pulse Survey file (survey period: 3/1/2023-3/13/2023) 
    - **pulse2023_puf_58_2023_2Q.csv** - 2023 2Q US Census Bureau Household Pulse Survey file (survey period: 6/72023-6/19/2023) 
    - **pulse2023_puf_60_2023_3Q.csv** - 2023 3Q US Census Bureau Household Pulse Survey file (survey period: 7/26/2023-8/7/2023) 
    - **pulse2023_puf_63_2023_4Q.csv** - 2023 4Q US Census Bureau Household Pulse Survey file (survey period: 10/18/2023-10/30/2023) 

- **Full Year data files created by notebooks:** 
    - **Note:  The files will be overlayed if you run the create analysis data file notebooks** 
    - **pulse2021_survey_data.csv** - 2021 Full Year Household Pulse Survey file created by the **create_2021_analysis_data_file.ipynb** notebook 
    - **pulse2022_survey_data.csv** - 2022 Full Year Household Pulse Survey file created by the **create_2022_analysis_data_file.ipynb** notebook 
    - **pulse2023_survey_data.csv** - 2023 Full Year Household Pulse Survey file created by the **create_2023_analysis_data_file.ipynb** notebook 

- **How to run:** 
    - You don't need to run the notebooks to create the pulse survey data files unless you make some changes to the create data file notebooks. 
    - Run the **covid_analysis_plots.ipynb** notebook to see the plots of **COVID vs. Anixous, Worry, Interest, and Down** responses. 
    - If make changes to the data files or the plots, you may break the notebooks, so be careful.  I have copies of all of this, so no worries if 
    - you break something. 

- Census Database Website for Pulse Surveys: https://www.census.gov/programs-surveys/household-pulse-survey/datasets.html#phase3.10