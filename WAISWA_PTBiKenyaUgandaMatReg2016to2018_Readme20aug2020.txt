This PTBiKenyaUgandaMatReg2016to2018readme.txt file was generated on 2020-08-20 by Elizabeth Butrick


GENERAL INFORMATION

1. Title of Dataset: PTBiKenyaUgandaMatReg2016to2018: Maternity Register Dataset

2. Author Information
	A. Principal Investigator Contact Information
		Name: Dilys Walker
		Institution: University of California San Francisco
		Address: 550 16th St, San Francisco CA
		Email: Dilys.Walker@ucsf.edu

	B. Associate or Co-investigator Contact Information
		Name: Peter  Waiswa
		Institution: Makerere University school of Public  Health
		Address: Old Mulago  Hospital  Kampala
		Email: pwaiswa@musph.ac.ug

	C. Alternate Contact Information
		Name: Elizabeth Butrick
		Institution: University of California San Francisco
		Address: 550 16th St, San Francisco CA
		Email: Elizabeth.Butrick@ucsf.edu

3. Date of data collection : 2016-10-01 through  2018-03-31

4. Geographic location of data collection : Migori County, Kenya and  Busoga Region, Uganda

5. Information about funding sources that supported the collection of the data: Bill and Melinda Gates Foundation


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: Open Access license

2. Links to publications that cite or use the data: 
Waiswa P, Higgins BV, Mubiri P, et al. Pregnancy outcomes in facility deliveries in Kenya and Uganda: A large cross-sectional analysis of maternity registers illuminating opportunities for mortality prevention. PLoS One. 2020;15(6):e0233845. Published 2020 Jun 1. doi:10.1371/journal.pone.0233845

3. Links to other publicly accessible locations of the data: 

4. Links/relationships to ancillary data sets: This data is a subset of the data collected  for  the East  Africa  Preterm Birth  initiative trial in  Kenya and Uganda.

5. Was data derived from another source? yes/no
	A. If yes, list source(s): 
East Africa Preterm Birth Initiative trial in Kenya and  Uganda. 
Protocol paper: Otieno P, Waiswa P, Butrick E, et al. Strengthening intrapartum and immediate newborn care to reduce morbidity and mortality of preterm infants born in health facilities in Migori County, Kenya and Busoga Region, Uganda: a study protocol for a randomized controlled trial. Trials. 2018;19(1):313. Published 2018 Jun 5. doi:10.1186/s13063-018-2696-2


6. Recommended citation for this dataset:
Waiswa P, Higgins BV, Mubiri P, et al. Pregnancy outcomes in facility deliveries in Kenya and Uganda: A large cross-sectional analysis of maternity registers illuminating opportunities for mortality prevention. Dataset,  doi:doi_10.7272_Q6ZG6QFC__v3


DATA & FILE OVERVIEW

1. File List: 

KUfacility_register_data_for_uploadWaiswaetalPLOSONE.xlsx, dataset in Microsoft Excel.

2. Relationship between files, if important: NA

3. Additional related data collected that was not included in the current data package: 
Data collection continued on into 2019, but was not included because  follow up was ongoing and it was  not used in  this analysis.
Additional data including  study identifiers and dates of   service were collected but excluded  to  remove identifiers.
Free text data  on  delivery complications and  outcomes was collected but not used  in this  analysis and thus excluded.

4. Are there multiple versions of the dataset? yes/no Yes
	A. If yes, name of file(s) that was updated: KUfacility_register_data_for_upload  
		i. Why was the file updated? File originally provided still contained  dates which have now been removed.
		ii. When was the file updated? 18 Aug 2020


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
Protocol paper for the parent study: Otieno P, Waiswa P, Butrick E, et al. Strengthening intrapartum and immediate newborn care to reduce morbidity and mortality of preterm infants born in health facilities in Migori County, Kenya and Busoga Region, Uganda: a study protocol for a randomized controlled trial. Trials. 2018;19(1):313. Published 2018 Jun 5. doi:10.1186/s13063-018-2696-2

Data were extracted from facility  based  maternity  registers by  study team members using  an ODK data  capture screen on a laptop  or  tablet. Data  were compiled in SQL, checked for completeness  or duplication, and exported as a  csv file. Analysis was performed in SPSS and STATA

2. Methods for processing the data: 
<describe how the submitted data were generated from the raw or collected data>
Entries were identified as  deliveries if at  least one of the following  was documented: 1-minute Apgar score, birth weight, infant sex, birth outcome, baby discharge status.  When  delivery and  discharge stats  could not be  distinguished Apgar scores  were used to  differentiate stillbirths from live births  experiencing  neonatal  deaths

3. Instrument- or software-specific information needed to interpret the data: 
All analyses except Fisher’s  exacts  were conducted in SPSS23.  Fisher’s exacts were performed in STATA 14

4. Standards and calibration information, if appropriate: NA

5. Environmental/experimental conditions: NA

6. Describe any quality-assurance procedures performed on the data: 
Unique maternal record identifiers were used to link maternal and neonatal data


7. People involved with sample collection, processing, analysis and/or submission: 
The  PTBi field teams in Kenya and Uganda collected  the  data.  Processing of the parent dataset was done in collaboration between in-country data  managers and a UCSF  data manager.  Analysis for  this paper was performed by  the  second  author (BH). Submission of  the manuscript was led by  BH. Submission  of the dataset was led  by  EB, overall program manager of the  parent  study.


DATA-SPECIFIC INFORMATION FOR: [FILENAME]


1. Number of variables: 24

2. Number of cases/rows: 61018

3. Variable List: 
<list variable name(s), description(s), unit(s)and value labels as appropriate for each>
id dataset id	
country	 differentiate by country	1,2
facility_coded	Health  Facility Code  1-23 HF001 through  HF023
referral_in Describes if mother was referred into the hospital from another hospital ‘Yes’=1;’No’ =0		
apgar_1	Infant's apgar score at 1  minute
apgar_5	Infant's apgar score at 5  minutes
sex	Sex of infant at birth Male, Female, Not_Indicated
baby_discharge_status	Describes the status of the baby at discharge ‘Alive’; ‘Unknown’; ‘Stillbirth’; ‘Died_Before_Discharge’;
multiple Indicates if mother delivered more than one baby ‘1 = single, 2 = twin, 3 = triplets, 4 = quadruplets 	
bba	record  contains designation  that baby  was born  before  mother’s arrival at the  facility 1= BBA
doc_abortion record  contains documentation  that the pregnancy  outcome was a  spontaneous abortion 1=Abortion	
doc_iufd record  contains designation that the fetal outcome was intrauterine fetal demise 1=IUFD 	
record_type Designates whether record was considered a birth or not	
c_mothers_age_cat Mother's age category	≤19, 20-24, 25-29, 30-34, ≥35, missing	
c_mother_status	Describes the status of the mother upon discharge from the maternity ward, as documented in the maternity register. ‘Discharged_Alive’; Discharge_Alive_with_Fistula'; ‘Died’; ‘Transferred_to_Another_Facility’; ‘Ran_away_or_Left_Before_Being_Discharged’; ’Ran_Away_with_Fistula’; 'blank_missing_dont_known' 
c_cat_ga Categorical GA  groups	
c_cat_bw Categorical BW groups	
c_mode_of_delivery Mode of Delivery ‘Normal_Vaginal_Delivery’; ‘Caesarean_Section’; ‘Dilatation_and_Curettage’; ‘Born_Before_Arrival’; ‘Laparotomy’; ‘Hysterectomy’; ‘Manual_Vacuum_Aspiration’; ‘Vacuum_Extraction’; 'Blank_Missing_Dont_Know' 	
quarter	coded designation of quarters to enable data aggregation
c_baby_status	Baby's Status at Delivery ‘Baby_Born_with_Defect’; ‘Fresh_Still_Birth’; ‘Macerated_Still_Birth’; 'Immediate_Neonatal_Death'; 'Live_Birth'
c_birth_outcome	Describes the outcome of the birth ‘Live_Birth’; ‘Unknown’; ‘Fresh_Still_Birth’; ‘Macerated_Still_Birth’; ‘Undefined_Still_Birth’; 'Unknown'
c_birth_weight_g2 Birthweight in  grams scale

4. Missing data codes: 
blank=missing

5. Specialized formats or other abbreviations used: 
