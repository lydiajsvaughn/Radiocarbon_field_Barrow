# Radiocarbon_field_Barrow
Analysis of 2012-2014 field radiocarbon data from Barrow, AK

Data used in this analysis are stored in the NGEE-Arctic data repository.  radiocarbon_field_Barrow_2012_2013_2014.csv and flux_CO2_CH4_Barrow_2012_2014.csv can be accessed at http://dx.doi.org/10.5440/1364062

Description of files:

(1) surface_chamber_atm_correction.Rmd corrects raw radiocarbon measurements from static chambers for background atmosphere contamination

(2) chamber_14C_plots.Rmd generates plots of ecosystem respiration rates and radiocarbon contents

(3) profile_14C_plots.Rmd generates plots of soil pore-space 14CO2 profiles

(4) C13endmember_names.rds is a vector of plot IDs with CO2 concentrations greater than 10x atmosphere

(5) naming.csv associates all chamber IDs with names according to this project's naming conventions

(6) bulk_soil_14C_correction.Rmd uses radiocarbon measurements made from bulk soil and evolved CO2 at the end of a soil incubation to calculate the radiocarbon abundance of bulk soil prior to the incubation 
