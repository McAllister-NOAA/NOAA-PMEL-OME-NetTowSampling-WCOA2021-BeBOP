---
# MIOP terms
methodology_category: sample collection
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: 'biodiversity assessment objective [OBI:0001969]'
analyses: 'filtration [OBI:0302885], environmental material collection process [OBI:0600012]'
geographic_location: 'North East Pacific Ocean [GAZ:00013765]'
broad_scale_environmental_context: 'marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]'
local_environmental_context: 'oceanic epipelagic zone biome [ENVO:01000035]'
environmental_medium: 'sea water [ENVO:00002149]'
target: 'fresh specimen [NCIT:C84517]'
creator: 'Sean McAllister, Meghan Shea'
materials_required: filtration [OBI:0302885]
skills_required: 'ship operations, net tow deployment, organismal preservation, organismal identification'
time_required: 180
personnel_required: 7
language: en
issued: 2026-04-07
audience: scientists
publisher: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies'
hasVersion: 1.1.0
license: 'CC0 1.0 Universal'
maturity level: operational

# FAIRe terms
samp_category: sample
env_broad_scale: 'marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]'
env_local_scale: 'oceanic epipelagic zone biome [ENVO:01000035]'
env_medium: 'sea water [ENVO:00002149]'
habitat_natural_artificial_0_1: 0
samp_collect_method: '20µm Rita, 75µm/200µm Vertical, 505µm Neuston, 100µm/335µm Bongo net tows'
samp_collect_device: 'cod end, plankton jar'
samp_size: 250
samp_size_unit: mL
---

# NOAA PMEL OME/Carbon Net Tow Collection Protocol - West Coast Ocean Acidification (WCOA) cruise 2021

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Julian Herndon | Carbon, NOAA PMEL | | 2021-06-18 |
| Meghan Shea | Stanford  |  | 2021-07 |
| Jordan Chancellor | University of Southern California | | 2021-07 |
| Kelcey Chung | Southern California Coastal Water Research Project	| | 2021-07|
| Sean McAllister | Ocean Molecular Ecology, NOAA PMEL/UW CICOES | 0000-0001-6654-3495 | 2026-04-07 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |


### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 0.1.0 | 2026-04-07 | Initial beta release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration
|OME	|Ocean Molecular Ecology|
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE| Personal protective equipment |
|RO| Reverse Osmosis|
|UW| University of Washington

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |


## BACKGROUND

### Summary


### Method Description and Rationale


### Spatial Coverage and Environment(s) of Relevance


### Personnel Required


### Safety


### Training Requirements


### Time Required to Execute the Procedure


## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For a singular cast with three unique samples taken (one sample per Niskin):

| DESCRIPTION               | PRODUCT NAME AND MODEL                                    | MANUFACTURER      | QUANTITY | REMARK                                                                                                                                |
| ----------------| ----------------------- | ------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Durable equipment**   |  |           |          |                                                                                                                                       |
| Bucket | 5-gallon bucket   | Generic  | 3    | Used as a catchment for water draining out of the sample sterivex |
| **Consumable equipment**  |     |         |          |     |
| **Chemicals** | |   |          |  |
| 100% molecular grade EtOH | 200 proof molecular biology grade ethanol| Fisher Scientific | 6000 μL  | Can be substituted with generic, must be 200 proof and molecular biology grade   |
| **Optional Equipment** | |   |          |  |

## STANDARD OPERATING PROCEDURE

From Cruise Report (URL):

Summary: 

During WCOA 2021, we conducted a biological station almost every evening, with a CTD cast and a series of net tows, including:
2 20 µm Rita net deployments
1 200 µm Vertical net deployment
1 75 µm Vertical net deployment
2 505 µm Neuston net deployments
1 Bongo net deployment with 2 335 µm nets
1 Bongo net deployment with 1 100 µm net and 1 200 µm net

On a typical night, the full net evolution would take 2-3 hours. During WCOA 21, we deployed nets at 31 distinct biological stations, with 216 individual nets deployed over the course of the cruise (62 Rita nets, 50 vertical nets, 57 Neuston nets, and 47 Bongo nets). Samples from the nets were processed with a combination of bulk preservation, picking of individual organisms, and imaging with a PlanktoScope; all processing types will require additional analysis after the cruise to produce cruise data. 

Personnel: 
Net Deployments: Bryce Dewees (NOAA, RHB), Sophia Tigges (NOAA, RHB) Meghan Shea (Stanford), Noah Gluschankoff (Stanford), Chris Ikeda (NOAA, PMEL) 
Preservation & Picking: Kelcey Chung (SCCWRP), Jordan Chancellor (USC) 

Net Rigging & Preparation: 
**more images of all net rigging in this Google Photo album**

Rigging:
A line was attached to the Rita net opening with a bowline knot and a large shackle was zip-tied onto the opening to help the net sink well. 

The Neuston net came pre-rigged, but the bridle was re-configured to allow the weight (80 lbs) to be properly attached to the bottom of the net with quick release links. Using fishing line and metal crimps, the SeaGear flow meter was attached diagonally in the center of the frame.

The vertical nets came partially rigged, but we re-attached the nets to the frames more securely using two half-hitches between each grommet. We then added three guide lines from the frames (knotted to attach), through the D-rings on the sides of the nets, down to ~1 foot beneath the bottom of the cod end (spliced to a shackle for attachment) to create a connection point to attach the weight (50 lbs) with a quick release link. In response to some initial tangling, we secured these rib lines in place to each of the external D-rings (rather than just running them through the rings). Using fishing line and metal crimps, the TSK flow meters were attached in the center of the frame. 

Bongo nets were attached to the frames using designated hose clamps that came with the nets. The hose clamps were then taped over with duck tape to add extra reinforcement and cover any sharp edges. Holes were drilled in the sides of each Bongo net to give a place to attach the General Oceanics flow meters using fishing line and metal crimps. A shackle was added to the top of the center piece of the frame to attach the net to the ship’s winch, and a shackle and quick release link were added to the bottom of the frame to create a place to attach the weight (80 lbs). 

Cod Ends:
To protect the cod ends from bumps against the side of the ship, bumpers were added to the bottom of each using hose clamps inside tygon tubing, with electrical tape wrapped around to secure. (NOTE: This would be easier with tygon tubing larger than the hose clamp. Our tubing was close to the same size as the hose clamp, so we cut it into small segments to make it easier to string onto the hose clamp.) 

Because we did not have 505 µm cod ends, we removed the mesh from several of our back-up cod ends and replaced it with 505 µm mesh. (NOTE: we used a combination of silicon glue and PVC piping glue, neither of which worked particularly well. A two-part epoxy would probably be best). 

All cod ends were attached to the bottom of the nets using hose clamps that came with the cod ends. When possible, the hose clamps in the groove of the cod end, and above the bottom seam of the net, to prevent the net from sliding. All hose clamps were taped over with electrical tape to protect the net from any sharp edges. 

Calibration:
The General Oceanics flow meters (for Bongos) came pre-calibrated. These flow meters were filled with water per the instructions included with the flow meters. The water in the flow meters was topped off once in the middle of the cruise, and probably could have been topped off more frequently. 

The TSK (for verticals) and SeaGear (for Neustons) flow meters were not pre-calibrated. However, their values were compared against the GO flow meters for realistic flow rates.

The Sensus Ultra pressure sensors were sent to a fixed depth on the CTD to verify their accuracy and record any discrepancies between them (calibration files in Pressure Sensor Files folder in Net Tows). 

Organization:
Using a paint pen, all pressure sensors were labelled with the net they would be used with, so they could be easily attached to the same net each time. Using colored electrical tape, the bottom of each net and the top of each cod end was given a unique color code, so that the cod ends could be easily matched to their respective nets. This color code was also used on the data sheets and the coolers used to store the cod ends after retrieval. 

Net Deployments:
Typically, we deployed the vertical nets first, followed by the Neuston nets, followed by the bongos. The biomass in the vertical nets would help inform the parameters used for the bongo nets. The Rita net would either be deployed during the biological station CTD cast (if a deep enough cast for the computer operator to handle the net event logging) or at the end of the net evolution (to allow time to run the PlanktoScope sample afterward). 

For all nets except the hand-deployed Rita, the bridle would be attached to the winch with a shackle (with a zip tie through it for extra security). In addition, the attachment clips on the cod ends were always taped over with electrical tape to ensure they could not open accidentally during deployment. 

For the Rita net, the net would be rinsed with saltwater and then deployed by hand over the side of the ship while the ship was stationary. It would be held at the surface for 3 minutes (recorded with a stopwatch) and then retrieved and rinsed very gently with saltwater. The Rita net would be deployed identically twice.

For the vertical nets, a pressure sensor would be attached to the top of the bridle with a zip tie and the TSK flow meter would be reset before each deployment. The net would be rinsed with saltwater, laid out on deck to check for tangles, and attached to the winch. A 50 lb weight with guide line would be attached to the bottom of the net rigging with quick links. With the ship stationary and the guide lines down, the survey tech would raise the net as high as possible, and then boom out so that the net frame was over the edge of the deck. The scientist assisting with deployment would lower the weight down using the guide line until the net rigging took the tension, at which point the line would be released and the net would be fully boomed out and sent down to the target depth (100 m, or ~20 m above bottom depth, whichever was more shallow) at 30 m/minute and then brought up at 30 m/min. Unless wind conditions were too challenging, the net would be rinsed with saltwater while hanging next to the ship, and then recovered by the survey tech and scientist pulling up together on the net rigging to bring the weight back on deck. After full retrieving the net, the flow meter would be read. We would deploy the 200 µm vertical net first, followed by the 75 µm vertical net. 

For the neuston net, the SeaGear flow meter would be reset before each deployment. The net would be rinsed with saltwater and attached to the winch. A 80 lb weight would be attached to the bottom of the net bridle with quick links. To deploy, the survey tech would guide the frame and weight up over the side of the science deck, and the scientist would guide the net itself over the side of the ship, throwing the cod end at the last possible moment (to prevent it from swinging back and forth and hitting the side of the ship). The neuston would be lowered down to just beneath the surface (deep enough that it infrequently exited the water between waves) and towed for 20 minutes, with the ship speed between 1-2 knots (enough to keep the net spread out and not bunched). Unless wind conditions were too challenging, the net would be brought back to the side of the deck, the flow meter would be read (to prevent it from spinning more during retrieval/rinsing), and the net would be rinsed with saltwater while hanging next to the ship. The scientist would then pull up the cod end by hand while the survey tech guided the weight and the frame back on deck. The neuston would be deployed twice during each evolution, with the same net but a new cod end attached (so we wouldn’t have to wait for the picking team to finish with the original cod end before deploying again). 

For the bongo nets, the General Oceanics flow meters would be recorded before each deployment (but not reset), and a pressure sensor would be attached to the top of the frame with a zip tie. The nets would be rinsed with saltwater and attached to the winch. An 80 lb weight would be attached to the bottom of the net frame with quick links. To deploy, the survey tech would guide the frame and the weight up over the side of the science deck, and the scientist would guide the net itself over the side of the ship, throwing the outboard cod end first followed by the inboard cod end to try to prevent the nets from twisting on themselves during deployment. If possible, another scientist would help the survey tech guide the frame. Using a wire angle chart, the wire out required to reach the target depth at an ideal wire angle of 45° would be determined (usually 141 m wire to reach 100 m target depth), and the winch would wire out at 30 m/min. A scientist would monitor the wire angle while the net was in the water, and the ship speed would be adjusted as needed to keep the wire angle in the target range of 38-52°. The ship speed was typically between 1-2 knots while towing the Bongo nets. Once the wire out value was reached, the net would be paused if necessary to adjust the wire angle, and then retrieved at between 10-30 m/min, depending on how much biomass was in the vertical nets. A scientist would continue to monitor the wire angle during recovery. Unless wind conditions were too challenging, the net would be brought back to the side of the deck, the flow meters would be reach (to prevent them from spinning more during retrieval/rinsing), and the net would be rinsed with saltwater while hanging next to the ship. The scientist would then pull up the cod ends by hand while the survey tech (and an additional scientist, if available) guided the weight and the frame back on deck. We would deploy the bongo net with two 335 µm cod ends first, followed by the bongo net with one 100 µm and one 200 µm cod end. 

After deployment, all nets would be rinsed thoroughly in freshwater and stored in a fish tote on deck. 

To increase efficiency, we would set up the next net in the evolution at the back of the deck while the previous net was in the water, and we would re-attach and tape the cod ends onto the nets before we put them away so they would be ready for the next station. We also had a designated cooler for each net, so that the deployment team could put the cod end in the cooler and set it aside easily if the picking team was not on deck. 

Processing: 

Rita Net & PlanktoScope:

For the first Rita net, the cod end would be gently tapped against the bottom of the sink to remove any excess water. Then, the contents would be poured into a 250 ml Nalgene bottle, the cod end mesh would be rinsed gently with filtered seawater (made before the deployment by filling a squirt bottle with seawater passed through the Rita net mesh), and any remaining liquid would be added to the Nalgene bottle. Buffered ethanol would be added (approximately the same volume as seawater in the bottle) and the sample would be stored in the fridge. 

For the second Rita net, the cod end would be gently tapped against the bottom of the sink to remove any excess water. Then, the contents would be poured into a 250 ml Nalgene bottle, the cod end mesh would be rinsed gently with filtered seawater (made before the deployment by filling a squirt bottle with seawater passed through the Rita net mesh), and any remaining liquid would be added to the Nalgene bottle. The Nalgene bottle would be gently inverted to mix the sample, and ~18 ml of sample would be added to three scintillation vials (a little bit into each vial at a time, also to help mix the sample). One scintillation vial would be set aside for the PlanktoScope, and the other two would have ~2 ml of formalin added and be stored at room temperature. 

The PlanktoScope sample would be filtered immediately through a homemade 200 µm sieve (since the flow cell was only 200 µm wide) and the PlanktoScope would be turned on and rinsed with 25 mL of DI water three times. The sample data would be entered into the PlankotScope software (latitude, longitude, time of sample etc.), and sample would be gently poured into the syringe (at an angle, to decrease pressure on cells during the pour), and 3 mL would be slowly passed through the PlankoScope to clear out any freshwater in the tubing (NOTE: the PlanktoScope protocol wanted the tubing to be dried between the freshwater rinses and the sample processing, but I had trouble with air bubbles being introduced when the sample was added, so I kept a small amount of freshwater fully in the tubing before I introduced the sample). With the sample visible in the flow cell, the focus would be adjusted and fluidic acquisition would be set up (pumped volume: .02 mL, 0.5 seconds before image to stabilize) and 500 images of the sample would be taken (monitoring for bubbles or other issues during the acquisition). (NOTE: It was often tricky to get the focus right, so I would check the images in the Gallery as soon as acquisition started and stop the acquisition and readjust as needed). After fluidic acquisition, the rest of the sample would be passed through the PlanktoScope to remove it, and the system would be cleaned again with 25 mL of DI water three times. 

Abbreviated Bulk Preservation Protocol

Following each deployment, cod ends were sieved through a net of the same mesh size and preserved according to the following protocol:

| Net | Size | Preservation Method | Storage Method | Notes |
|-----|------|---------------------|----------------|-------|
|Rita|20|Buffered Ethanol|Room Temperature|250 mL jar|
|Rita|20|Buffered Formalin|Room Temperature|3 X 20 mL scintillation vials|
|Vertical|75|Buffered Ethanol|Room Temperature||
|Vertical|200|Buffered Ethanol|Room Temperature||
|Neuston|505 (\#1)||-80 degC|Preserve what is left after picking, excluding gelatinous material|
|Neuston|505 (\#2)|Buffered Ethanol|Room Temperature||
|Bongo|100|Buffered Ethanol|Room Temperature||
|Bongo|200|Buffered Ethanol|Room Temperature||
|Bongo|335 (\#1)|Buffered Ethanol|Room Temperature||
|Bongo|335 (\#2)|Buffered Formalin|Room Temperature||

Bulk Cod End Preservation Notes

Bottle size was determined based off the amount of organic material obtained from each net tow

Picking for species of interest was carried out from both of the Neuston tows. If the requested number of species individuals could not be obtained from the Neuston nets, picking was continued from the Bongo 335 tow. 

Excess salps and pyrosomes from Neuston and Bongo tows at stations where numbers were highly abundant were sieved from initial tow and discarded after the desired individuals were preserved. 

Individual Sample Collection Summary

Target Preservation Quantities for each Station in Order of Priority
| Species | What For | How Many | What Container | Preservation Method | Storage Method |
|---------|----------|----------|----------------|---------------------|----------------|
|Dungeness Crab Megalopae|Biomarkers|6-8|Individual Cryotubes|Flash Frozen|-80 degC|
|Dungeness Crab Megalopae|Transcriptomics|2-3|Individual Eppendorf Tubes|RNAlater|-20 degC|
|Dungeness Crab Megalopae|Exoskeleton Dissolution|6|Scintillation vial|Buffered Ethanol|Room Temperature|
|Dungeness Crab Megalopae|DA|2|Single Eppendorf Tube||-80 degC|
|Dungeness Crab Megalopae|Isotopes|5|whirlpack||-80 degC|
|Krill|Biomarkers|6-10|Individual Cryotubes|Flash Frozen|-80 degC|
|Krill|DA|3-4|Aluminum Foil||-80 degC|
|Krill|Fatty Acids|3|Aluminum Foil||-80 degC|
|Krill|Isotopes|20-50|Whirlpack||-80 degC|
|Fish|Biomarkers|7-10 of same species|Individual Cryotubes|Flash Frozen|-80 degC|
|Fish|DA|1 Anchovy, 1 Myctophid, 1 Market Squid|Aluminum Foil||-80 degC|
|Fish|Fatty Acids|3 Myctophids|Aluminum Foil||-80 degC|
|Pyrosomes||2-3|Whirlpack||-80 degC|
|Salps||2-3|Whirlpack||-80 degC|
|Red Crab Zoea||10-20|Scintillation vial|Buffered Ethanol|Room Temperature|
|Pteropods|SEM/light shell dissolution|10|Scintillation vial|Buffered Ethanol|Room Temperature|
|Pteropods|µCT|10|Scintillation vial|Buffered Ethanol|Room Temperature|
|Pteropods|Shell Isotope|10|Scintillation vial|Buffered Ethanol|Room Temperature|
|Pteropods|Drexel University|20|Scintillation vial|Buffered Ethanol|Room Temperature|
|Pteropods|DA|15-20|Single Eppendorf Tube||-80 degC|
|Pteropods|Isotopes|10-15|Whirlpack||-80 degC|
|Pteropods|Onboard Sequencing|10-15|PCR tubes|95% EtOH|Room Temperature|
|Pteropods|Transcriptomics|15|Split into three Eppendorf Tubes|RNAlater|-20 degC|
|Copepods|Isotopes|~500|Whirlpack||-80 degC|
|Copepods|DA|10|Single Eppendorf Tube||-80 degC|

Data Management: 

During net evolutions, the scientist operating the computer in the main lab would use the ship’s event logger to record when nets entered the water and were retrieved from the water (and when nets reached depth, for the vertical and bongo nets). The event logger was set to record times, latitude, longitude, station #, net type, net #, speed over ground, water temperature, and bottom depth each time an event was logged. On deck, one scientist maintained a laminated data sheet with a Sharpie to record additional necessary data (flow meter readings, bongo wire angles, etc.). 

After each net evolution, one scientist would fill in a hard copy data sheet for each net type, with a combination of information from the deck data sheet and the deployment log. For each station, all of these hard copy data sheets were scanned and saved in a batch. The information from these data sheets was also added to an Excel master data file, organized by net type. 

The pressure sensors from the bongo and vertical nets were removed after each net evolution so the data could be uploaded. The depth reached for each net was recorded on the hard copy data sheet (above), and a file with the pressure information and raw data was saved for each net. 

The type and number of jars preserved from each net was also recorded and added to the Excel master data file. 

Additional Lessons Learned: 
For the on-deck data sheet, a grease pen might have been better to write with than a Sharpie. 
For ease of deployment, all flow meters were kept permanently attached to the net frames (but vigorously rinsed with freshwater after each deployment). For the most accurate flow meter readings, it would probably be better to remove the flow meters after each deployment and soak in freshwater; using zip ties as the final point of attachment would probably make this easiest. 
Originally the plan was to stop the Bongo tow at the target depth for a period of time, and to also stop at the DCM depth on the way back up to the surface, but due to high biomass recovered even just from a tow to depth and then back to surface, we did not end up using this deployment plan. If there are plans to do deployments with different timings or strategies, it  would be important to test those deployments before the first station if possible so that you can make sure there won’t be too much biomass for the picking team to deal with. 
You need infinitely more electrical tape than you think you need (and get the good stuff: Amazon Basics is just not great!). Also lots of zip ties. 


###DETAILED PROTOCOLS

  WCOA 2021 Biological Net Sampling Protocols

Rita net (three deployments; 20 µm nets):
Deployment and Recovery Team: Meghan Shea, Alexandra Rodier
Sample analyses (PlanktonScope): Meghan Shea; Preservation: Alexandra Rodier
Purpose: To collect phytoplankton samples (down to 20 µm in size). Request permission from the Bridge before deploying the net so they can make a log entry. Before deploying, fill out the Rita Net Sample Log and ensure you have the sample container and preservative ready.  If there is a flow meter, record the value (left to right) before deploying. Use the 1-meter markings on the line to determine depth. Secure the open end of the line to the cleat and deploy by hand from the ship to a depth no greater than 3 m and recover by hand (2-3 minutes). Be sure to let the Bridge know when you start and when you are done with the sampling, particularly if CTD operations are happening at the same time as when you are deploying the net and you have permission from the ship to deploy. Deploy by hand and record information on the Rita Net sample log sheet. Labels needed for the first two samples.
Three samples will be collected: 1) phytoplankton composition- preserved in buffered ethanol 250 ml jar; 2) phytoplankton composition- preserved in buffered formalin - 20mL scintillation vial with formalin; and 3) PlanktonScope- 20 ml scintillation vial with no preservative to be run through the PlanktonScope: Meghan will conduct the filtration. 
Labels needed for the 1) and 2) above.


Vertical Net Tow Sampling (two deployments for different net sizes (75 µm and 200 µm) fitted with a TSK flowmeter. 
Deployment of 75 µm mesh size net with subsequent buffered ethanol preservation; the sample needs to be stored at 2⁰C.
Deployment of 200 µm mesh size with buffered formalin preservation.

Deployment and Recovery Team: Survey Technician, Meghan Shea, Alexandra Rodier 
             Sample preservation: Kelsey Chung (SCCWRP), Jordan Chancellor (USC)

Purpose: Collect samples for pteropods, copepods, krill, small fish and measure species abundance, evidence of dissolution, biomarkers, eDNA, and isotope geochemistry. The goal is to better understand the relationships between environmental stressors and biological responses. Vertical nets (three deployments) for different net types (75 µm and 200 µm) fitted with a TSK flowmeter. Before deploying fill out the Vertical Net Sample Log Sheet and make sure you have a sample container and preservative or a cooler ready as appropriate.  Ensure that the cod end is securely attached.  Check to make sure the flowmeter (TSK) is secure and functioning correctly.  Record the serial number and the value on the flow meter in the Vertical Net Sample Log Sheet.  Attach the pressure sensor and record its serial number. Two scientists will be ready to deploy the net.  When the command is given to deploy the net over the side the scientist holding the bridle will guide it up and then over the side as the boom moves outboard, and the other scientist will help where needed.  The net will be lowered through the water column with the cod end below the ring so it does not sample on the way down. The retrieval process will be similar with the two scientists recovering the bridle, weight and cod end at the direction of the Survey Technician.
 
The vertical net is deployed vertically, while the ship is stationary, wire speed of 30m/min on deployment and recovery. Vertical deployment is to a maximum depth of 100 m. When at deepest depth, immediately retrieve the net at 30 m/min. If the depth is less 100 m stay above 10 m above the bottom, keeping in mind the total length of the net and weight suspended below it.  The weight should be attached to the bridle and linked to with line to extend 1 ft below the cod end so that the cod end does not support the weight of the weight.  Record date, time, location, water depth, name of samplers, weather state, winds, currents, etc. on your field log sheets.  Rig the nets, attach weights, check equipment for holes, tangles, and loose fittings. Reset the TSK flow meter to zero or record initial counts. Deploy the net at 30 meters/min wire speed to desired depth. Complete the Vertical Net Tow Log Sheet for the station, recording the flow meter readings, and location. Note anything unusual or any issues with the sampling or equipment, especially for the Vertical tow nets. After collection, rinse down the sides of the net with seawater so that all the material goes into the cod end. After the cod ends are removed and are relocated safely out of the way, rinse nets down with fresh water, including the rings and cod end. Rinse all flow meters with fresh water as well. Power-washing the net (being careful of flow meters) may help dislodge phytoplankton buildup. Check equipment periodically. Look over entire net carefully to check for holes. Check the flow meters to see if they seem to be spinning at their normal rate. Store equipment carefully in a secure location. Store vertical net with flow meter down, so that the metal won’t rub on the net and wear holes into it. Do not step on the nets. Try not to allow stiff folds/creases to form in the nets. Preserve the 75 µm sample in buffered ethanol. Preserve the 200 µm sample using neutrally-buffered formalin, diluting to make the final formalin concentration ~5% (i.e., add 35 ml of buffered formalin to a 500 ml sample jar containing your sample, top off to the threads with seawater to create a 5% formalin solution). It is handy (and safest) to use a squeeze bottle with a measured reservoir dispenser. Top off the jar to the bottom of the threads with seawater to prevent dehydration. Close tightly and swirl to mix.  Label the jar with a Sharpie (won’t wipe off) with: date, time, station, type of tow (vertical), mesh size, depth of tow, and flow meter reading It is preferable to also make a label for the inside of the jar (in case the outside label gets wiped off, or lids switched accidentally, etc) using waterproof paper and pencil.  Label the same things as the lid, plus the latitude/longitude position of the station sampled if it is not a consistent location.

Neuston Net Tows 50 cm by 100 cm (two deployments; 505 µm)
          Deployment and Recovery Team: Survey Technician, Meghan Shea, Noah Gluschankoff, 
         Sample Picking and Preservation: Kelcey Chung, Jordan Chancellor 
Assisting with the material preparation: Tanner Waters, Blanca Alvarez, Elijah Catalan (preparing the labels, jars, preparation of the liquid, assisting Kelcey/Jordan as needed)

Purpose: Collect crab larvae, krill, pteropods and small fish (anchovies, myctophids), tunicates and likely copepods for abundance, transcriptomics, isotopes, biomarkers (see the priorities in the detailed Google Doc).
 Tow at or near the surface (0-5 m) for 15-20 minutes at a speed of 2-3 knots (see attached Figure 1). Floats and small weights are placed at the top and bottom corners of the bridle, respectively, to keep the opening vertical during deployment (see Figure 1. below). A line is attached to the two bottom corners to hold the weight in place below the net and help hold it in a vertical position.  (Figure 1. below). A line is attached to the two bottom corners to hold the weight in place below the net and help hold a vertical position. We will utilize the ship’s speed to control the net position at/near the surface during the operation in the water. Before deploying fill out the Neuston Net Sample Log Sheet and ensure you have the sample container and preservative or a cooler are ready as appropriate.  Make sure that the net is clean, the cod end is securely attached and the flow meter (SeaGear) is functioning correctly, is securely attached and spins freely.  Record the starting value (left to right) of the flow meter before deploying.  Attach the pressure sensor and record the serial number. Deployment will occur from the starboard side of the ship.  We will have one Survey Technician directing the operation to maintain safety and using the radio to exchange information with the winch operator while giving instructions to the scientists directly. Two scientists will be ready to deploy the net: one holding the brindle and one holding the other end of the net and cod end.  When the command is given to deploy the net over the side the scientist holding the bridle will guide it and the weight over the side so it doesn’t contact the ship and the other scientist will hold onto the net and cod end and wait until the bridle is in position with the boom extended outboard and carefully release the net and cod end aft of the bridle away from the ship so it can lay out onto the water downstream of the bridle. The retrieval process will be similar with the two scientists recovering the bridle, weight and cod end at the direction of the Survey Technician. After collection, rinse down the sides of the net with seawater so that all the material goes into the cod end. Once all the material is in the cod end, empty into the coolers (both nets into individual coolers) to start the picking procedure. After the cod ends are removed and the samples are placed in the cooler, rinse nets down with fresh water, including the bridle and cod end. Rinse all flow meters with fresh water as well. Rinsing down the nets (being careful of flow meter) may help dislodge any phytoplankton buildup. Check equipment periodically. Look over entire net carefully to check for holes. Check the flow meters to see if they seem to be spinning at their normal rate. Store Neuston nets with flow meter down, so that the metal won’t rub on the net and wear holes into it. Do not step on the nets.


Processing of the Neuston Tows: 
TRANSFER THE content of each NEUSTON NET INTO THE COOLER AND START TAKING OUT THE ORGANISMS. MAKE SURE THAT THE TEMPERATURE OF WATER IN THE COOLER STAYS APPROX THE SAME AS WHEN COLLECTED, SHOULD NOT BE WARMED!
all the samples taken out need to be catalogued in detail and described for both, 1st and 2nd Neuston
1st Neuston net to come out for selective picking out of organisms (see below under d- priorities); whatever remains is preserved at -80°C (EXCEPT FOR THE BIGGER GELATINOUS MATERIAL, which should be removed).
c.  	2nd Neuston net:  because it is unlikely to get all the organisms out from the 1st Neuston net, we should empty the 2nd Neuston into a second cooler as well. First pick all the organisms out from the 1st Neuston, and then go to the 2nd Neuston. The organisms that are preserved separately can be selected from both nets without identifying which net (1st and 2nd) is coming from; for example, we get 10 individuals from neuston 1 but need 5 more- which we can get them from neuston 2- we do not have to keep the track if we get them from the from 1st or the 2nd net.

IMPORTANT: We will take all the species/individuals that we need from the Neuston nets, including: krill, Dungeness crab, fish (anchovies, myctophids), squid, pteropods, tunicates). If we get everything from both Neuston nets, we do not have to pick out samples from the Bongos. This will keep the life stage of the organisms comparable, as well as not make sure we are not interfering with too many samples onboard (this will also save a lot of time and energy).

For copepods - visually make an estimate how many individuals are in the 1st net of the Neuston- if sufficient (approx. 500 is needed), then preserve the 1st Neuston bulk net at -80°C; (also make sure to remove larger gelatinous material) – again, we are NOT picking out the copepods but just wanting to come as close to the number as possible.  Preserve the remainder of the 2nd Neuston in buffered ethanol.

Priorities for the Neuston net in the following order of priorities (based on the sensitivity of the material):

i. For Dungeness crabs megalopae 
1. 	6-8 individuals Dungeness megalopae for biomarkers (Katja, Amelie, Jonna)– each Dungeness crab megalopae individual is preserved in separate cryotube (or aluminum foil if too big for the cryotube or if cryos do not come), quick flash-freezing, then store at -80°C (clarify with Katja that this is the case); THIS IS TIME SENSITIVE – PROCESS AS QUICKLY AS POSSIBLE! this will be done at selected 15 stations- see a map with these stations
2-3 ind Dungeness crab into RNA Later for transcriptomics (Jordan) - TIME SENSITIVE – PROCESS AS QUICKLY AS POSSIBLE! At selected 10-15 stations
6 individuals Dungeness crabs megalopae preserved in buffered ethanol (for SCCWRP for exoskeleton dissolution) – in one tube
2 Dungeness for DA- preserved at -80°C (Kelcey, SCCWRP)
6. 	5 Dungeness crab for isotope work (S Litvin) put in a provided bag and preserve at -80°C
7. A few individuals from various transects for the onboard sequencing- to work with Matt and Sean for selection (north, south, offshore, onshore organisms)
Additional task in the Southern California Bight, we are collecting ‘red crab zoea’ (10-20 individuals, for SCCWRP/Kelcey)- put in buffered ethanol - this to be collected on the SCB and wherever they occur northwards on the transect 12 (Monterrey) and 13 (Point Conception) - Kelcey in charge.

ii. For krill: 
1. 	6-10 for biomarkers – not separating per species (Katja, Amelie, Jonna)–each krill individual is preserved in a separate cryotube, quick flash-freezing, then store at -80°C- - TIME SENSITIVE – PROCESS AS QUICKLY AS POSSIBLE! map is provided over which transect to do it. → ID of two species not necessary
2. 	3-4 individuals for DA (preserve at -80°C in aluminum foil), preserve at -80°C (For Nina).
3. 	3 krill individuals – for fatty acids (Hunt)- store at -80°C in the aluminum foil- three krill individuals can be place together in aluminum foil, as long as they are separated apart – 
→ ID of two species desirable - no microscope needed for evaluation - see the protocols to distinguish between the species
ID: If Euphasia pacifica is present, then collect only E. pac. If E. pac is not present, then collect the krill species that are present. If no krill present, then no samples.  
NOT SO TIME SENSITIVE COLLECTION (MAYBE 10-20 MIN).
4. 	20-50 krill individuals (FOR ISOTOPES - S Litvin); preserve at -80°C in special bags provided by S Litvin (see the protocols sent to you); Less TIME SENSITIVE COLLECTION (PROCESS TIME AROUND 15-20 MIN).

iii.  For fish: 
7-10 individual fish for biomarkers (should be the same species, either anchovies, or myctophids but make sure we have 7 individuals of the same species (Katja, Amelie)– individual is preserved in separate cryotube (or aluminum fold if too big for the cryotube), quick flash-freezing, then store at -80°C; - TIME SENSITIVE – PROCESS AS QUICKLY AS POSSIBLE! at the selected 16-20 stations.
1 anchovies, 1 myctophid fish and 1 market squid for DA (for Nina); preserve at -80°C (in aluminum foil, separate species separately)
3 individuals myctophid fish– for fatty acids (Hunt)- store at -80 in the aluminum foil- at some 15-20 stations
Put all remaining anchovies, myctophids and squid all in one bag (for Steve Litvin); preserve at -80°C; some rough notes on what the sample contains would be useful and greatly appreciated. 

iv. For tunicates:  
Preserve tunicates (incl. salps and pyrosomes; rather than doliolids)- I SELECTED FOUR TRANSECT WHERE TUNICATES SHOULD BE SAMPLED (SEE THE MAP)
at 8-12 stations across the entire coast (we will provide the map at which approx stations).
v. For copepods 
preserve 5-10 copepods at -80°C for DA (PREFERRABLY IN CRYOVIALS)
all remaining copepods (a batch remained from the 1st neuston net into the bag for the isotope samples – WE ARE NOT PICKING OUT INDIVIDUAL COPEPODS (500 individuals minimum!).
An approximate number of copepods should be estimated (visual estimation only) if not enough, then more copepods should be added from 335 µm Bongo net.

Sample Picking Notes
Let’s say our target is 50 Dungeness crabs:
1) If we get 50 organisms from the Neustons🡪 OK! No need to open any other nets,
2) If we get 40-45 organisms from the Neuston 🡪 reduce the number of organisms for each partner (give each objective one less crab),
3) if collected 40 and less crabs 🡪 you first check if you got sufficient amount of Dungness on the last two stations that are proximate to the regions,
 if YES, do not open 335 um Bongo, but reduce the number of crabs preserved ethanol (for dissolution),
IF no, only then should you open 335 um Bongos and try to get as many as possible.
4) if collected 5-10 organisms- then this is not the station where we are collecting Dungeness crab, wait for the next station.


Bongo Net Tow Sampling (two deployments of two nets for different net sizes (1st; 100 µm and 200 µm and 2nd; 335 µm and 335 µm) fitted with a General Oceanics flowmeter
100 µm and 200 µm samples preserved in buffered ethanol.
1st 335 µm sample preserved in buffered ethanol; 2nd 335 µm sample preserved in buffered formalin.
Deployment and Recovery Team: Survey Technician, Noah Gluschankoff, Meghan Shea, Alexandra Rodier 
Sample picking (only if not sufficient from the Neuston) and preservation: Kelcey Chung (SCCWRP), Jordan Chancellor (USC).

Purpose: Collect samples for pteropods, larval echinoderms, copepods, krill, small fish and measure species abundance, evidence of dissolution, biomarkers, eDNA, and isotope geochemistry. The goal is to better understand the relationships between environmental stressors and biological responses. Rig the nets, attach weights, check equipment for holes, tangles, and loose fittings. The Bongo tow is an oblique tow which is deployed at a 45° wire angle to approximately 100meters (150 meters wire out). The bongo nets (two deployments) for different net types (100 µm, 200 µm and 335 µm) should be fitted with a General Oceanics flowmeter. Before deploying fill out the Net Sample Log Sheet and make sure you have a sample container and preservative or a cooler ready as appropriate.  Ensure that the cod end is securely attached.  Check to make sure that the flowmeters are attached to each of the nets and are secured and functioning correctly.  Record the serial number and the value on the flow meter in the Net Sample Log Sheet.  Attach the pressure sensor and record the serial number. Two scientists will be ready to deploy the net: one holding the bridle and the other holding the other end of the net and cod end.  When the command is given to deploy the net over the side the scientist holding the bridle will guide it over the side so it doesn’t contact the ship and the other scientist will hold onto the net and cod end and wait until the bridle is in position with the boom extended outboard and carefully release the net and cod end aft of the bridle away from the ship so it can lay out onto the water downstream of the bridle.  One of the scientists will guide the weight as it rises off the deck and over the side. The retrieval process will be similar with two scientists recovering the bridle, weight, and cod end at the direction of the Survey Technician. 

Get depth of water in meters from the deck officer before you deploy.  Find depth along the x-axis and follow it upward to where it intersects the center oblique line (45°).  Follow the nearest horizontal line below the intercept over to the y-axis.  This is how much wire, in meters, to put out for the net tow. Check the flowmeter numbers and record them on the tow sheet. Record the first 5 numbers reading from left to right. You are now ready to deploy the Bongo. The ship speed necessary to tow the Bongo will vary from ship to ship and with weather conditions. Generally, to get a 45° wire angle upon deployment, the ship's speed should be 1.5 - 2.0 knots. The purpose of having a 45° wire angle is to ensure proper sampling depths at all times during the tow. Also, it is virtually impossible to deploy the Bongo frame with less than a 45°wire angle without causing the nets, frame and wire to wrap around each other. When the ship is at the proper speed, lower the Bongo into the water. Make sure the winch operator zeros the winch counter at the surface before starting down. A stopwatch should be started to record the sinking time. Record the begin tow time on the tow sheet. The wire should be let out at 30 meters/min going down to a maximum target depth of 100 m. Be sure to maintain the net for 5 min at the target depth of 100 m. Begin to raise the bongo net slowly from a target depth of 100 m to a target depth of 25 m at 5 m/min (or whatever is the slowest reasonable speed) and stop and hold that 25 m target depth for 2 min. Raise the Bongo net from 25 m to the surface at 5 m/min (or whatever is the slowest reasonable speed) and hold at the surface for 2 min.  If the depth is less 100 m stay above 20 m above the bottom. Record the wire angles on the way down, when the Bongo reaches the desired target depth, then again at a target depth of 25 m, and on the way back to the surface. There should be a total of approximately 4 wire angle measurements for a standard tow. The acceptable wire angle range is between 38° & 52°, 45° being optimal. This range is to be adhered to strictly, especially in the rising part of the tow. When the Bongo is at the surface, stop the watch and record the towing time on the log sheet. The towing time should be about 35 minutes. Record the end flowmeter numbers. The 80 lb weight should be attached to the bridle and linked to with line to extend 1 ft below the Bongo frame.  Reset the General Oceanics flow meter to zero or record initial counts. Complete the field sheet for the station, recording the flow meter reading, wire angle, date, time, location, water depth, approximately 4 wire angle measurements, names of samplers, weather state, winds, currents, etc. on your field log sheets. Be sure to note anything unusual or any issues with the sampling or equipment, especially for the bongo tows. After collection, rinse down the sides of the net with seawater so that all the material goes into the cod end. After the cod ends are removed and are relocated safely out of the way, rinse nets down with fresh water, including the rings and cod end. Rinse all flow meters with fresh water as well. Check equipment periodically. Look over entire net carefully to check for holes. Check the flow meters to see if they seem to be spinning at their normal rate. Store bongo nets with flow meter down, so that the metal won’t rub on the net and wear holes into it. Do not step on the nets. Try not to allow stiff folds/creases to form in the nets. Check the flow meters to see if they seem to be spinning at their normal rate. Store equipment carefully. Hang the Bongo frame from the vertical steel angle iron pole secured to the deck and store the net in the fish tote secured on deck next to the steel angle iron pole.  Do not step on the nets. Try not to allow stiff folds/creases to form in the nets. Preserve one 335 µm sample using neutrally-buffered formalin, adding enough to make the final formalin concentration ~5% (i.e., add 35 ml of buffered formalin to a 500 ml sample jar containing your sample, top off to the threads with seawater to create a 5% formalin solution). It is handy (and safest) to use a squeeze bottle with a measured reservoir dispenser. Top off the jar to the bottom of the threads with seawater to prevent dehydration. Close tightly and swirl to mix. Label the jar with a Sharpie if it is a matt surface (won’t wipe off) with: date, time, station, type of tow (vertical or bongo), mesh size, depth of tow, and flow meter reading It is preferable to also make a label for the inside of the jar (in case the outside label gets wiped off, or lids switched accidentally, etc) using waterproof paper and pencil. Label the same things as the lid, plus the latitude/longitude of the station sampled if it is not a consistent location.


Picking out from the 1st net (100 µm)- all Bongos in buffered ethanol
echinoderm larval for RNA Later for transcriptomics (Jordan, USC)
echinoderm larval for shell dissolution (UCLA) and preserved in buffered formalin (difficult to pick out, time permitting- otherwise just preserved in ethanol)
The rest of the 100 µm preserved in buffered ethanol

Picking out from the 1st net (200 µm)
PTEROPODS would already be picked from the Neuston net, we only open Bongos if Neuston did not provide sufficient individuals. this is 

For pteropods –
a. 10 pteropods of L. helicina for SEM/light shell dissolution analyses- preserve in buffered EtOH (SCCWRP); 
b. 10 individuals for uCT preserve in buffered EtOH (SCCWRP);
c. 10 individuals for shell isotope (Karen)
	a to c should be in one scintillation vial; b should be in a separate jar (scintillation vial with 20ml) 
d. 20 pteropods from a selected 6-7 stations in the Bight for Drexel University (for Bryce, Jocelyn)- preserved in buffered EtOH (see the stations that this needs to be collected from)- Kelcey to collect and preserve in buffered ethanol; not time sensitive -see the Excel spreadsheet for this.
e. 15-20 pteropods (Limacina helicina) selected and preserved at -80 for DA (Nina)
f. 10-15 pteropod of Limacina helicina for isotope work (Litvin) store at -80C in the prescribed bags
g. 10 individuals (Limacina helicina) from various transects for the onboard sequencing- to work with Matt and Sean for selection (north, south, offshore, onshore organisms).

Please note: on the line 14- we will collect pteropods from all different nets: Neuston and Bongo and vertical.

Ethanol exchange to happen around 24 hours after collection
In charge for the ethanol exchange: Tanner, Blanca with help from Kelcey/Jordan  
Exchanges for all the samples that were preserved using buffered ethanol (Rita, Vertical, Neuston, Bongo). Decant old liquid and replace with new ethanol making organisms are not lost. Kelcey to start with this and then teach the rest of the team. 

We could generalize as follows: 
1) Neuston (505 µm) and Bongo (335 µm) sample could have ethanol decanted without using the sieve. Do not mix the sample in any regard (so that the content is settled as much as possible) and only decant the upper ethanol out. Once you see that the organism could go out, stop and replace the ethanol to the upper end (as much) of either the 250 or the 500 ml jar.
2) Bongo (200 µm and 100 µm) and Vertical (100 µm, 200 µm), could do the same as under 1), but ONLY if the sample is properly settled. Here, you can start with decanting to a smaller extent and then proceed the pipette until the safety limit. Then replace with the ethanol to the full extent.
3) Vertical (75 µm) and Rita (20 µm) net samples that are stored in 250 jar and 20ml scintillation vial)- repeat the same procedure as under 2) but exercise more caution because smaller organism are trapped at or near the surface of the ethanol and DO NOT settle. Hence, most advisable for 3) is to actually remove the ethanol with the pipette (we have a really big pipette among the materials in Bednarsek box from WCOA 2016 cruise). Please, remove the ethanol by touching the pipette along the jar wall and proceed slowly by sucking it up. Then replace with the ethanol to the full extent, both in the jars and scintillation vials. 


Jar label Information required
Cruise Name: WCOA 2021; Station:
Date, Time (please write out the month) 
Net type and mesh size, depth towed:
How Preserved (buffered ethanol or buffered formalin)
Asterisk if animal removed. 
Name of Collector


Below are some details on what should be recorded.
 sample location (this ID needs to match up with the most proximate CTD station name)
 type of net and depth (and depth mostly mandatory when it deviates from the depth we have in the protocols)
 date of collection
 what was preserved in (buffered ethanol or formalin, etc...)
 and then add the asterisk to the label if any material was taken out for some other purposes (like preserved neuston net labels will have a lot of asterisks because we will take out of that net)
 name of the collector



### WCOA21 Guidelines for Formalin & EtOH additions

Formalin for preserving phytoplankton cells from Rita net and Niskins.
Buffer w/25g of Hexamethylenetetramine to 500mL
|Ci|Vi|Cf|Vf|
|--|--|--|--|
|37|250|18.5|500|
|18.5|2.2|2|20|
|18.5|2|1.85|20|

For 20mL scint vials add 2mL of the final solution (target ~2% final formaldehyde)

Formalin for preserving vertical, Bongo and Neuston tows
Buffer with Borax to a pH of ~8.2.
|Ci|Vi|Cf|Vf|
|--|--|--|--|
|37|13.5|2|250|
|37|27.0|2|500|
|37|15.0|2.2|250|
|37|30|2.2|500|

For 250mL bottles, add 15mL of the second to last dilution using squeeze bottle reservoir (final [~2.2%] formaldehyde)
For 500mL bottles, add 30mL of the last dilution using squeeze bottle reservoir (final [~2.2%] formaldehyde)

By volume (5% as per Keister SOP)
25mL Formalin to 250mL bottle
|Ci|Vi|Cf|Vf|
|--|--|--|--|
|37|25|3.7|250|

5% vol/vol results in 3.7% formaldehyde final

EtOH (95%)
Buffer with NH4OH until acheiveing a pH of ~8.2


### Preparation


### Sampling

### Filtration

### Sample Preservation

### Storage

### Quality Control


### Basic Troubleshooting Guide

**Issue 1:** 

**Solution:** 


## REFERENCES

## APPENDIX
  
