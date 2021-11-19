# tahoe_lab_inc_analysis
Analysis of laboratory incubations of periphyton collected from Lake Tahoe as part of a project funded by the Lahontan Regional Water Quality Board.

This also contains analysis of tahoe nearshore network data provided by Sergio Valbuena.

Incubation Datasheet Column Meanings:
Chamber: Chamber ID #

drained_wt_g: weight in grams of chamber and rock with no water

filled_wt_g: same as above, but with water added to chamber

Tank_a: ambient experiment tank #

Tank_e: enriched experiment tank #

water_wt_g: weight in grams of water inside chamber

water_vol_L: volume of water in chamber in liters

total_wet_wt_g: total wet weight of periphyton harvested from rock in grams

PP_wt_g, chla_wt_g, PC_PN_wet_wt_g: wet weight (in grams) subsamples of periphyton for each specific analysis

PC_PN_tin_wt_g, AFDW_tin_wt_g: weights of pre-tared sample containers for PCPN and AFDW

SWW_g: sediment wet weight (grams) of AFDW subsample

SDW_60C_g: sediment dry weight (grams) of AFDW subsample after drying at 60C for 24 hrs

SCW_500C_g: sediment combusted weight (grams) of AFDW subsample after combusting at 500C for 1hr

total_DW_g: total dry weight (grams) of periphyton scaled up to the whole rock

total_AFDW_g: total ash-free dry weight (grams) of periphyton scaled up to the whole rock (using methods from Scott Hackley of TERC; AFDW = SDW_60C-SCW_500C)

rock_SA_m2: rock surface area covered by periphyton in sq. meters approximated as an ellipsoid and assuming an average periphyton coverage of 67% 


########## Important Incubation Details:####################

  210301 Tahoe City incubation:
    -used average surface areas for all rocks since rocks were separated from their associated chamber numbers before these measurements were taken thus surface area measurements may not be as accurate as other incubations
    -filtered periphyton samples using GF/F's instead of nitex mesh, thus biomass measurements may be slightly different than other incubations
    
  210315 Tahoe City incubation:
    -over-enriched the chambers to around 570ug/L NO3-N and NH4-N and SRP to around 823ug/L (150% of target NO3-N and NH4-N concentrations and 259% of target SRP conc.). Thus, enriched incubations may over-estimate nutrient effect compared to other incubations. Target NO3-N and NH4-N concentrations were 400ug/L and target SRP conc. was 318ug/L.
  
  210421 Pineland Incubation:
    -under-enriched nutrients to 45ug/L NH4-N and NO3-N (~11% of target concentrations) and 67ug/L SRP (~21% of target concentrations) so nutrent effect might be underestimated in these incubations.
    -There was significant differences in periphyton biomass between the ambient and enriched incubations in april due to sloughing, the average AFDW/m2 decreased by 27% between the ambient and enriched incubations which could potentially confound results. This possibly led to lower surface area-normalized metabolic rates between the ambient and enriched incubations.
    
  210613 Pineland Incubations:
    -Performed ambient and enriched incubations on the same set of rocks and paired biomass msmsnts for these incubations.
    -Enriched chambers to the correct nutrient concentrations of 400ug/L NO3-N and NH4-N and 318ug/L SRP.
    -Data was lost from first ambient incubation, thus it was performed again later that evening.
    -Data from one presens 4-channel device quit recording during the dark portion of the enriched incubation, but the issue was fixed and data was recorded in a different file and added to the main data file later.
    
  Metabolism Data QA/QC methods:
      -11/16/21: went through all experiments (up to 211010 experiment) and made sure timings of NEP and ER portions of DO curves matched with notes and DO data spreadsheets.
                  - also went through and flagged chambers with R^2 values of metabolic rates below 0.9
                  - made sure that if pre- and post-NEP ER curves were averaged to get ER rates that they both agreed and matched up, and if not I flagged them if the % difference was over 20%. Some chambers did show considerable (~50%) variation in ER rates taken from multiple portions of ER curves (tank 2 in 4/21/21 experiment notably).