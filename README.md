# Description
This replication package contains the Stata code and raw spreadsheets
needed to create the state-level and substate-level minimum wage dataset
described in Vaghul and Zipperer (2016).

# contents of code/
Run the following do-files to create the state and substate-level extracts.
You will need to change the $home directory in these do-files to match
your directory setup.
state_mw.do         create state-level data
substate_mw.do      create substate-level data (requires output of state_mw.do)

# contents of rawdata/
These spreadsheets are the raw data called by the do-files above:
VZ_SubstateMinimumWage_Changes.xlsx                   substate-level changes
VZ_HistoricalMinWage_Changes_6.27.2016.xlsx           state-level changes
VZ_HistoricalMinWage_Federal_Changes_6.27.2016.xlsx   federal changes
FIPS_crosswalk.xlsx                                   misc. state geography
