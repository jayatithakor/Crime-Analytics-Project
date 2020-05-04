Crime Analytics:


This folder consists of three Notebooks and a data folder.


Notebooks:
The notebooks are set up in sequential order. 
1. Data EDA and visualization- Includes loading various datasets and exploring the features and categories. Performing visualization. Does not include cleaning or transformations.
2. Data Cleaning: Mainly includes transforming several columns to numeric and integrating data from various datasets into one dataframe which is exported to csv
3. Data Modelling: Assigning target and features for the models. Test,train split. Running various classification models and evaluating the accuracy score and confusion matrix.
Includes results for feature importance. 


Data Folder:
1. UCR65_18.csv- Uniform Crime Report data summarizing all homicides and homicide clearances reported from 1965 to the present
 
2. Database.csv- Dataset from kaggle. case-level data from Supplementary Homicide Report from FBI  and 30,500 additional homicides obtained by freedom of information act.Cleaner version.



Data Dictionary:
MAP: Murder Accountibility project
For the final dataset used in the modelling notebook:


Record ID: Unique record identifier 
Agency Code:The alphanumeric variable describing the Originating Agency making the report. The first two digits describe the state of the Originating Agency, the next three digits usually represent the county in which the agency is located (according to an FBI numbering scheme) and the last two digits describe the agency’s number within the state.
Agency Name: Variable describing the name of the law enforcement agency making the report.
Agency Type:Describing the type of law enforcement agency making the report like Sheriff, County Police,Municipality,Tribal Police etc
City: Metro area or locality of the homicide.
State: State where the homicide was reported
Year: Year of homicide (or when the victim's body was recovered.)
Month: The month of homicide occurrence or when the victim’s body was recovered.
Incident: A number describing the case number within the month in which a homicide occurred. This does not necessarily correspond to the actual case number used inhouse by police agencies. It is used to assist in building a unique record number for each case and to differentiate each case reported within the same month. 
Crime Type: variable defining whether the report was “Murder or Nonnegligent manslaughter” OR “Manslaughter by Negligence.”
Crime Solved: whether Offender was identified at time report was made 
Victim Sex:variable representing whether the victim was  Male, Female or “Unknown” gender, usually for conditions in which incomplete remains were recovered. 
Victim Age:– A three-digit numeric variable describing the age in years of the victim. To allow for simpler mathematical calculations, MAP has changed the original alphanumeric coding of “NB” for newborn and “BB” for infant to a numeric value of zero to indicate the victim had not achieved a full year of life. A value of 99, as in the original numbering scheme, represents all victims 99 or older. A value of 999 represents victims whose age was not reported, usually because the victim was unidentified and the age was unknown.
Victim Race: Represents the race of the victim : White,Black, Asian or Pasific Islander, American Indian or Alaskan Native.
Victim Ethnicity: variable representing whether the victim was “Hispanic Origin” ,“Not of Hispanic Origin” or “Unknown or Not Reported.” It should be noted that many agencies decline reporting the ethnicity of victims and offenders.
Perpetrator Sex:variable representing whether the perpetrator was  Male, Female or “Unknown” 
Perpetrator Age: – A numeric variable describing the age in years of the Perpetrator. When the Perpetrator was not identified at the time of the report, age was reported as 999. A value of 99 represents all offenders 99 or older.
Perpetrator Race: Represents the race of the Perpetrator : White,Black, Asian or Pasific Islander, American Indian or Alaskan Native, or ‘Unknown’-usually in conditions in which the Perpetrator had not been identified at the time of the report.
Perpetrator Ethnicity: variable representing whether the Perpetrator  was “Hispanic Origin” ,“Not of Hispanic Origin” or “Unknown or Not Reported.”
Relationship: Variable describing the relationship between the victim and the offender
Weapon: variable representing the weapon used in the crime. 
Victim Count: The number of additional victims (not counting the victim included in the current record) included in the Supplementary Homicide Report’s incident record
Perpetrator Count: The number of additional offenders (not counting the offender included in the current record) included in the Supplementary Homicide Report’s incident record
Record Source: FBI or MAP
Rate: Rate of clearance of homicides by agency.
