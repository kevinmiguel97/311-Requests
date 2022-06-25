# CS506 Boston 311 Equity Analysis

Repository containing code related to Boston University's Spark Project on Boston 311 service request reports in collaboration with District 7 City Councilor Tania Fernandes.


<p align="center">
  <img width="700" src="https://i.imgur.com/5ShbvSk.jpg">
</p>

# Summary of Project Goals
The main goal of the project is to help [City Councilor Tania Fernandez](https://www.boston.gov/departments/city-council/tania-fernandes-anderson#:~:text=Councilor%20Anderson%20was%20elected%20to,part%20of%20the%20South%20End.), who represents Boston's District 7. We processed data from 311 requests, obtaining insightful information to better understand the needs of the District´s community. This dataset serves as a good indicator of how each district is being served by the city and as an approximation of how the city resources are distributed among different part of districts. This also enables questioning how District 7 compares to the remaining Boston Districts in terms of 311 requests. Knowing this information will help our client to have a better understanding of how to optimize the resources by allocating them on the specfic needs that require them the most. 

Real-time transparency is a future goal based on what we achieved on this project, as our client's plan is to keep exploring the data set generate from this project with future spark teams and generate a dashboard that allows everyone to clearly see how city authorities are responding to their needs.

# Summary of Main Findings
Main findings of the analysis can be found here:  [analysis_code.ipynb](https://github.com/kevinmiguel97/District-7-311-Requests/blob/main/Code%20delivered/analysis_code.ipynb)

Final report can be found here: [Final report](https://github.com/kevinmiguel97/District-7-311-Requests/blob/main/Reports%20delivered/Final%20report.pdf)

# Steps to Reproduce Analysis
#### Download the Data
Download the [Required Data](https://drive.google.com/drive/folders/1xIQco1FpzytSaH3loEESOFI1QvyXrm0X?usp=sharing)

#### Install Conda & Jupyter Notebooks
[Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
[Jupyter Notebook](https://jupyter.org/install)

#### Recreate the conda environment using the environment.yml from Required Data
In your conda accessible terminal run the command:

`conda env create -f environment.yml`

#### Open Jupyter Notebook with the code
After opening Jupyter Notebook using your newly created conda environment navigate to the Required Datasets that were downloaded.
Open the `analysis_code.ipynb`
On the header row of the Jupyter Notebook click Cell > Run All

# Links to Data
[Required Data](https://drive.google.com/drive/folders/1xIQco1FpzytSaH3loEESOFI1QvyXrm0X?usp=sharing)
