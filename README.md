<img width="192" alt="Screenshot 2024-05-24 at 12 25 48 PM" src="https://github.com/donmarcolaureano/seattle_crime/assets/140132043/76b003f5-3d4e-478a-a21b-488bf0c3c5dd">

# Seattle Crime Data
This dataset contains all of Seattle Police Department's records of reported crime from 2008 up until May 23rd, 2024 (when this repository was created). The dataset is updated daily and can be accessed via the link below.

## Data
The data for this project is too large for the github repository but it can be found <a href="https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5/about_data"> here </a>

Inspiration for this project is based off of Washington Association of Sheriffs and Police Chiefs <a href="https://github.com/donmarcolaureano/seattle_crime/tree/main/Inspiration">2022 Crime in Washington Annual Report </a>

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
| 100 Block Address  | Offense(s) address location blurred to the one hundred block |
| Blurred_Longitude Coordinate | Offense(s) spatial coordinate blurred to the one hundred block |
| Blurred_Latitude Coordinate |  Offense(s) spatial coordinate blurred to the one hundred block | 


## National Incident-Based Reporting System (NIBRS) Offense Codes

| Offense Code    | Offense Description  |
| --------------- | -------------------- |
| 23F  | Theft From Motor Vehicle |
| 220  | Burglary/ Breaking & Entering  |
| 290  | Destruction/Damage/Vandalism of Property |
| 23H  | All Other Larceny |
| 13B  | Simple Assault | 
| 240  | Motor Vehicle Theft  | 
| 23C  | Shoplifting | 
| 23G  | Theft of Motor Vehicle Parts or Accessories | 
| 13A  | Aggravated Assault  |
| 13C  | Intimidation  | 
| 90J  | Trespass of Real Property |  
| 23D  | Building  Theft From Building  | 
| 120  | Robbery   |
| 35A  | Drug/Narcotic Violations |
| 26B  | Credit Card/Automated Teller Machine Fraud |
| 90D  | Driving Under the Influence |
| 26F  | Identity Theft | 
| 26C  | Impersonation  |
| 26A  | False Pretenses/Swindle/Confidence Game | 
| 520  | Weapon Law Violations | 
| 90F  | Family Offenses, Nonviolent |
| 280  | Stolen Property Offenses  | 
| 90A  | Bad Checks  |
| 250  | Counterfeiting/Forgery   |
| 35B  | Drug Equipment Violations |
| 26E  | Wire Fraud |
| 40A  | Prostitution  |
| 11D  | Forcible Fondling | 
| 23A  | Pocket-picking |
| 11A  | Forcible Rape  | 
| 90G  | Liquor Law Violations  |
| 270  | Embezzlement | 
| 200  | Arson | 
| 100  | Kidnapping/Abduction |
| 210  | Extortion/Blackmail  | 
| 11B  | Forcible Sodomy | 
| 90B  | Curfew/Loitering/Vagrancy Violations |
| 23B  | Purse-snatching  |
| 09A  | Murder & Nonnegligent Manslaughter | 
| 370  | Pornography/Obscene Material | 
| 26G  | Hacking/Computer Invasion (new offense)   |   
| 11C  | Sexual Assault With An Object  | 
| 23E  | Theft From Coin-Operated Machine or Device | 
| 40B  | Assisting or Promoting Prostitution   | 
| 40C  | Purchasing Prostitution  |   
| 90H  | Peeping Tom |  
| 720  | Animal Cruelty (new offense) |  
| 36B  | Statutory Rape   |     
| 26D  | Welfare Fraud  | 
| 64A  | Human Trafficking, Commercial Sex Acts  |  
| 36A  | Incest  |    
| 09C  | Justifiable Homicide   |   
| 39A  | Betting/Wagering | 
| 09B  | Negligent Manslaughter  |    
| 90E  | Drunkenness (not DUI)   | 
| 510  | Bribery  |   
| 39B  | Operating/Promoting/Assisting Gambling  |     
| 64B  | Human Trafficking, Involuntary Servitude |     
| 39C  | Gambling Equipment Violations  |     

For more detailed information about each offense, the NIBRS process, and any other frequently asked questions please see the <a href="https://github.com/donmarcolaureano/seattle_crime/blob/main/Data/WA%20Uniform%20Crime%20Reporting%20Program%20NIBR%20codes.pdf"> Washington State Uniform Crime Reporting Program Handbook</a>

## Crime Database
Coming soon
