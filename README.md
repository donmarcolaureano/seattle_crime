<img width="192" alt="Screenshot 2024-05-24 at 12 25 48 PM" src="https://github.com/donmarcolaureano/seattle_crime/assets/140132043/76b003f5-3d4e-478a-a21b-488bf0c3c5dd">

# Seattle Crime Data
This dataset contains all of Seattle Police Department's records of reported crime from 2008 up until May 23rd, 2024 (when this repository was created). The dataset is updated daily and can be accessed via the link below.

## Data
The data for this project is too large for the github repository but it can be found <a href="https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5/about_data"> here </a>

## Data Dictionary
| Field Name     | Description  |
| ---------------  | -----------  |
| Report_Number   | Primary key/UID for the overall report. One report can contain multiple offenses, as denoted by the Offense ID |
| Offense_ID   | Distinct identifier to denote when there are multiple offenses associated with a single report |
| Offense_Start_DateTime  |  Start date and time the offense(s) occurred  | 
| Offense_End_DateTime  | End date and time the offense(s) occurred, when applicable  |
| Report_DateTime  |  Date and time the offense(s) was reporteed. (Can differ from the date of occurrence)
| Group_A_B  |  Corresponding offense group  |
| Crime_Against_Category  | Corresponding offense crime against category  | 
| Offense_Parent_Group |  Corresponding offense parent group |
| Offense  | Corresponding offense  |
| Offense_Code  | Corresponding offense code |
| Precinct  | Designated police precinct boundary where offense(s) occurred | 
| Sector  | Designated police sector boundary where offense(s) occurred  |
| Beat  | Designated police beat boundary where offense(s) occurred | 
| MCPP_Neighborhood  | Designated Micro-Community Policing Plans (MCPP) boundary where offense(s) occurred |
| Blurred_Address  | Offense(s) address location blurred to the one hundred block |
| Blurred_Longitude Coordinate | Offense(s) spatial coordinate blurred to the one hundred block |
| Blurred_Latitude Coordinate |  Offense(s) spatial coordinate blurred to the one hundred block | 
