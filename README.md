# Description
This replication package contains the Stata code and raw spreadsheets
needed to create the state-level and substate-level minimum wage dataset
described in Vaghul and Zipperer (2016).

## Contents of /code/
Run the following do-files to create the state and substate-level extracts.
You will need to change the ${home} directory in these do-files to match
your directory setup. Additionally, within the ${home} directory, you will need to create an exports/ and a release/ folder in order for the code to run. 

1. state_mw.do - creates a state-level data 
2. substate_mw.do - creates substate-level data (requires output of state_mw.do)

## Contents of /rawdata/
These spreadsheets are the raw data called by the do-files above:
* VZ_SubstateMinimumWage_Changes.xlsx - substate-level changes
* VZ_StateMinimumWage_Changes.xlsx - state-level changes
* VZ_FederalMinimumWage_Changes.xlsx - federal changes
* FIPS_crosswalk.xlsx - misc. state geography
