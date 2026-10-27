# BelusWarrenKeeleyTauber

Team name: Team Fast Fires
Team members: Trisha Belus, Ashlee Warren, Elizabeth Keeley, James Tauber
Research Question: What is the relationship between fast fires and forest type?
Is this different from the relationship between fast fires and topography?
Audience: Forest managers, urban/city planners, large private forest landowners, small private forest landowners. 

Data Dictionary

Row Representation:
Each row represents one day within each fire event.

Variable Definitions:
Variable: id
Description: Unique identifier of the fire event.

Variable: ig_date
Description: The earliest date contained in the event

Variable: ig_day 
Description: The day of the year of the earliest date contained in the event

Variable: ig_month 
Description: The month of the earliest date contained in the event

Variable: ig_year
Description: The year of the earliest date contained in the event.

Variable: last_date
Description: The latest date contained in the event

Variable: event_dur
Description: Duration of the event in days

Variable: tot_ar_km2
Description: Area burned in square kilometers for the entire event. 

Variable: fsr_km2_dy
Description: Total kilometers burned for the entire event divided by the duration of the fire event. 

Variable: mx_grw_km2
Description: Maximum daily fire growth per event in square kilometers

Variable: mn_grw_km2
Description: Minimum daily fire growth per event in square kilometers

Variable: mu_grw_km2
Description: Mean daily fire growth per event in square kilometers

Variable: mx_grw_dte
Description: Date of maximum fire growth

Variable: lc_code
Description: Numeric code for the landcover type extracted from the MODIS landcover product for the year preceding the fire. 

Variable: lc_mode
Description: Numeric code for the landcover type extracted from the MODIS landcover product for the year preceding the fire.

Variable: lc_name
Description: Character string of the landcover type from the year before the fire. 

Variable: lc_desc
Description: Character string description of the landcover type from the year before the fire. 

Variable: lc_type
Description: The landcover classification scheme used

Variable: eco_mode
Description: Modal ecoregion code

Variable: eco_type
Description: Which type and level of ecoregion classification was used (North america EPA (levels 1-3) vs World Wildlife Federation)

Variable: eco_name
Description: Character string of the ecoregion type where the event occurred.

Variable: tot_perim
Description: Total perimeter of the fire event. 

