# Module GG4257 (Creating Sustainable Cities with Spatial Data Science) Lab Assignment 2

**Content:** This repo contains the jupyter notebooks and relevant data for completing Lab Assignment 2 - which includes the challenges from the lab workbooks 4,5 and 6.

- [MainPage - Report](MainPage.ipynb) -> Assignment cover page which includes an introductiona and final remarks section
- [lab_4_challenges] -> Challenges from lab workbook 4: UA_LabWorkBook_4, focuses on Making Maps - Four challenges focusing on geographical mapping and visualisation
- [lab_5_challenges] -> Challenges from lab workbook 5: UA_LabWorkbook_5, focuses on Growth And Accessibility - Nine challenges involving spatial data, network analysis and accessibility methods
- [lab_6_challenges_1-6](lab_5/Challenges_1-6/lab_5_challenges.ipynb) and [Lab_6_Challenge_7](lab_5/Challenge_7/lab_5_challenge_7.ipynb) -> Challenges from lab workbook 6: UA_LabWorkbook_6, focuses on Geodemographics - Classification of Bristol's 2021 Census Output Areas using k-means clustering, PCA and mapping
- [IRP Proposal Slides](230005735_IRP_slides.pdf)— Independent Research Project proposal slide (PDF)

**Notes for reproducability:**
1) GitHub-> Clone or download the repository and open the notebooks in JupyterLab
2) Environment-> The notebooks were developed using the GG4257 ua Conda environment
3) Data-> The local datasets are included in the relevant lab folders where possible. External sources (including OpenStreetMap, Bristol Open Data and ONS/Nomis) are referenced within the notebooks
4) Execution-> Run the cells in order, as later cells may depend on earlier outputs. An internet connection is required for some API requests.
5) Documentation-> Code comments and Markdown explanations describe the methods, adaptations and results, with relevant references included.

*Other additional notes:*
One issue I repeatedly encountered was with Lab 5 Challenge 6, where the Overpass API repeatedly timed out when downloading building data. I have kept the intended code and documented the limitation so the analysis can be attempted again if the service is accessible.
For Lab 6, the relevant Census 2021 datasets and Bristol Output Area boundaries are included locally to help with reproducibility.
References: The main methods follow the GG4257 lab workbooks, with additional sources referenced in the individual notebooks and MainPage report.