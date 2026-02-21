# The-Stack-Overflow-Recommendations-Dataset-SORD-A-Large-Scale-Curated-Recommendations-Dataset-
A replication package accompanying paper  entitled _"The Stack Overflow Recommendations Dataset (SORD) – A Large-Scale Curated Dataset of Recommendations Related Stack Overflow Questions, Answers and Comments"_  <br>
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
<br>
## DOI 
[https://doi.org/10.6084/m9.figshare.31361758](https://doi.org/10.6084/m9.figshare.30948506)<br>
This repository contains the replication package of the paper submitted to the Data-in-Brief Journal entitled _The Stack Overflow Recommendations Dataset (SORD) – A Large-Scale Curated Dataset of Recommendations Related Stack Overflow Questions, Answers and Comments_

This method for curating the dataset has been designed, developed, and reported by the following investigators:
1. Ms. Arjumand Fatima (Department of Computer Science, Quaid-i-Azam University)
2. Dr. Onaiza Maqbool (Department of Computer Science, Quaid-i-Azam University)
   
For any information, interested researchers can contact us by sending an email to any of the investigators listed above. The detailed step-by-step procedure is given below.

## How to cite the package
Fatima, Arjumand; Maqbool, Onaiza (2025). Stack Overflow Recommendations Dataset (SORD) - Version 1.0 based on Stack Overflow Data Dump - October 2025. figshare. Dataset. https://doi.org/10.6084/m9.figshare.30948506.v1<br>
## Accessibility
Owing to the large size of the dataset including replication package and additional metadata, we have not uploaded the data on GitHub. This repository just explains the package while the data is available on Figshare.
## Data Dump Used
We have utilized the quarterly updated Stack Overflow data dump published in October 2025 which is described below.

| File Name  | File Size | No. of Records After Parsing |
|:---|:---:|:---:|
| Badges	| 5.99 GB	| 54,312,436 (54M)| 
| Comments	| 26.2 GB	| 91,315,031 (91M)| 
| PostHistory	| 172 GB	| 162,338,606 (162M)| 
| PostLinks	| 767 MB	| 6,535,632 (6.5M)| 
| Posts	| 98.4 GB	| 60,376,057 (60M)| 
| Tags	| 5.60 MB	| 66,046 (66k)| 
| Users	| 7.25 GB	| 30,088,388 (30M)| 
| Votes	| 22.3 GB	| 246,514,372 (247M)| 

## The Stack Overflow Recommendations Dataset (SORD)
We have curated Stack Overflow Questions, Answers and Comments containing one or more recommendation related keywords from the above mentioned data dump which are included in SORD as described below. We have included the results obtained from CONTAINS and LIKE-CONTAINS in the dataset. 
### Set of Keywords Used to Curate Data
We have used the following set of recommendation related keywords to filter questions, answers and comments potentially containing any sort of recommendations, present in the gigantic Stack Overflow data dump (published in October 2025) containing the data from its inception in 2008 till October 2025.
`Recommend`,`Advise`,`Advocate`,`Adopt`,`Suggest`,`Suitable`,`Praise`,`Favor`,`Support`,`Urge`,`Promote`,`Champion`,`Endorse`,`Commend`,`Propose`,`Oppose`,`Condemn`,`Reject`,`Disapprove`

### Data Included in SORD
| Data | Total Records | Substring Matching (LIKE) | Exact Matching (CONTAINS) |Substrings Other than Exact Match (LIKE-CONTAINS)|
|:---|:---:|:---:|:---:|:--:|
| Question Title |24,198,178|	 164,586 (0.68%)	| 73,901 (0.31%)| 90,685 (0.37%)
| Question Body  |	24,198,178| 2,646,945 (10.94%) |1,135,148 (4.69%)| 1,511,800 (6.25%)
| Answers |	36,063,114| 3,655,886 (10.14%) |2,228,118 (6.18%)| 1,427,770 (3.96%)
| Comments |	91,315,031| 4,014,709 (4.40%) |1,900,242 (2.08%) | 2,114,468 (2.32%)
### Additional Metadata Included
In addition to the above mentioend data we have also extracted additional meta-data from Stack Overflow data dump for enriching SORD which is as follows.
| Data | Total Records | Filtered Records Related to SORD|
|:---|:---:|:---:|
|Badges	|54,312,436	|34,830,450  (64.13%)|
|Tags	|66,046|	61,672  (93.38%)|
|Users	|30,088,388	|1,993,211  (6.62%)|
|Votes	|246,514,372	|50,725,814  (20.58%)|


```xml <row Id="82957" UserId="5246" Name="Teacher" Date="2008-09-15T08:55:03.957" Class="3" TagBased="False" />```


