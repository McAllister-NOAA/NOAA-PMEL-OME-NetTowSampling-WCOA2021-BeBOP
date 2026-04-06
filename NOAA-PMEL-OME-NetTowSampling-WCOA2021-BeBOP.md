---
# MIOP terms
methodology_category: sample collection
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: biodiversity assessment objective [OBI:0001969]





analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323], Lake Washington [GAZ:00008722], South Pacific Ocean [GAZ:00002418]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake biome [ENVO:01000252], estuary [ENVO:00000045]
environmental_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: Shannon Brown, Han Weinrich, Zachary Gold
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 120
personnel_required: 1
language: en
issued: 2025-11-14
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1.1.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
env_local_scale: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake biome [ENVO:01000252], estuary [ENVO:00000045]
env_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011]
habitat_natural_artificial_0_1: 0
samp_collect_method: CTD Niskin rosette, ROV, hand deploy
samp_collect_device: Niskin bottle, gravity bag
samp_size: 1000
samp_size_unit: mL
---

# NOAA PMEL OME eDNA Collection Protocol with Sterivex and Gravity Filtration

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
|Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-10-03|
|Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2025-10-03|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630 |2025-10-03|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump | https://github.com/marinednadude/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump.md |  1.1.1  | 2025-11-14 | Internal |
| NOAA-PMEL-OME_eDNA_Collection_Protocol_DiscFilters_VacuumManifold | https://github.com/Brown-NOAA/NOAA-PMEL-OME_eDNA_Collection_Protocol_DiscFilters_VacuumManifold_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_DiscFilters_VacuumManifold.md | 1.1.0  | 2025-11-14  | Internal |
| NOAA-PMEL-OME_eDNA_Sterivex_Extraction_Protocol_Centrifuge | https://github.com/marinednadude/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge/blob/main/NOAA-PMEL-OME_eDNA_Sterivex_Extraction_Protocol_Centrifuge.md | 1.1.4 | 2025-11-14 | Internal|

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-10-06 | Initial release |
| 1.1.0 | 2025-11-14 | Minor content revisions |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
| CTD | Conductivity Temperature Depth |
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration
|OME	|Ocean Molecular Ecology|
|PES|Polyethersulfone|
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE| Personal protective equipment |
|PVC| Polyvinyl chloride |
|qPCR|Quantitative Polymerase Chain Reaction|
|RO| Reverse Osmosis|
|ROV| Remotely Operated Vehicle|
|UW| University of Washington

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Conductivity, Temperature, Depth (CTD) sensor | Sensor used to measure temperature, conductivity, and pressure. Additional sensors are often attached to the frame of the deployable CTD (oxygen, chlorophyll, pH, etc.) to collect additional data. Often, Niskin bottles are attached to the same deployable metal frame as the CTD and ancillary sensors so that water parameter data are collected alongside Niskin water samples. Deployments of this suite of instruments and sensors on the same frame are often referred to as a "CTD cast". |
| Field blank | Sampling negative control. Typically, distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| Gravity bag  | A collapsible, sterile bag, similar in appearance to an IV fluid bag, used to filter water samples. When suspended above a filter capsule, water flows downward under the force of gravity, eliminating the need for pumps or power sources.|
| Niskin bottle  | Plastic cylindrical bottle of varying volumes for collecting discrete water samples. A stopper at each end of the bottle can be "cocked" open with an electronic or weight-triggered release mechanism, causing the stoppers to snap shut. This is remotely triggered, so the bottle closes at a prescribed depth. Often, multiple bottles are arranged on the same frame as a CTD and other sensors in a "rosette". |


## BACKGROUND

### Summary

Water collection and filtration protocol using sterivex filters and gravity bags to collect environmental DNA from marine and freshwater ecosystems. This collection and filtration protocol is used by the NOAA PMEL Ocean Molecular Ecology (OME) Group in place of [NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump](https://github.com/marinednadude/NOAA-PMEL-OME_eDNA_Collection_Protocol_Niskin/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump.md) when a more simplistic, portable filtration method is required for either more concentrated sampling or remote fieldwork. It is not used in place of the peristaltic pump protocol, as that protocol allows more control over the filtration speed and has less consumable waste.

### Method Description and Rationale

This protocol describes the collection and filtration of water samples through a 0.22 µm PES sterile filter capsule to capture eDNA and DNA-containing particulates. DNA will later be extracted from these samples for multi-locus metabarcoding and qPCR analysis. The protocol is intended for water collected with a Niskin bottle mounted on a ship-deployed CTD rosette sampler or ROV, but it can also be employed for samples collected by hand.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to filter eDNA from hundreds of seawater samples taken from coastal stations off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea, and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska) as well as freshwater samples from the freshwater Lake Washington. Samples collected range in depth from surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf).

### Personnel Required

One person with pipetting experience. Recommend research vessel experience, but not required.

### Safety

This protocol uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique and pipetting technique) is required to conduct this protocol. Experience with going to sea and sample collection under seagoing conditions is encouraged at a minimum; personnel should be trained in the filtering protocol in a laboratory/docked ship setting beforehand.

### Time Required to Execute the Procedure

The time needed varies widely based on the number and type of samples collected. For a majority of our sampling, Niskin bottles on a CTD rosette and/or ROV are triggered to collect at three depths (e.g., surface, 30m, and 10m off bottom). Then, depending on the study design and Niskin size, a singular sample or triplicate samples are collected from each Niskin. The depth of collection and number of samples affect the time required; for instance, a cast to 30 m may take 10 minutes, while a cast to 600 m may take over an hour. Collecting samples from the Niskins takes between 10-30 minutes, depending on access and whether the water is being used for other science. We've also collected samples using a bucket or by directly submerging bottles and/or gravity bags in sample water in situ, which takes significantly less time for collection.

The gravity bag filtration set-up for three singular samples takes on average 10 minutes. Pending the turbidity of the water, the filtering of a single sample takes 30-80 minutes, and then preservation takes 5 minutes. One benefit of the gravity filtration method is the simultaneous filtering of samples and thus better scaling, whereby more samples will increase the gravity bag filtration setup and preservation times linearly, while the actual filtering step will remain constant. The user can also walk away and complete other tasks while the gravity bags are filtering.

The total collection and filtering time for a singular cast with three Niskins triggered and one sample taken from each Niskin is 120 minutes (2 hours) on average.

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
| Pipettor: 100-1000 μL | Pipetman P1000  | Gilson | 1  | Can be substituted with any accurate pipettor.|
| Tubing  | 1/4" DEHP-Free polyvinyl chloride (PVC) Tubing   | Generic | 3  | Must fit the adaptor and output tubing on gravity bag   |
| Hose barb adaptors   | Male Luer Lock 1/4" Hose Barb Adapter | Generic           | 3        |               |
| Nalgene bottles| 1 L Nalgene wide-mouth lab quality amber HDPE bottles     | Thermo Scientific | 3        | Can be substituted with generic - must be opaque, well-sealing, and sterilizable. |
| Wash bottles  | Safety wash bottles 500 mL for EtOH, bleach, and RO water | VWR | 3   | Can be substituted with generic, but recommend purchasing different colored bottles for each reagent. Must be sterilized before use.  |
| Bucket | 5-gallon bucket   | Generic  | 3    | Used as a catchment for water draining out of the sample sterivex |
| Carabiners  | Carabiner clips | Generic    | 1    | Used to hang gravity bags    |
| Binder clips  | Large and medium binder clips | Generic    | 6    | Useful to secure sterivex to a bucket    |
|Screwdriver| Flathead tool for turning the locking mechanism on the gravity bag line| Generic| 1| Can be substituted with a coin or any flat, cleanable tool that fits into the locking mechanism slot| 
| **Consumable equipment**  |     |         |          |     |
| Gravity bags | Kangaroo 1000 mL feeding pump bags | Generic   | 3    | Recommend sterile, not required|
| 50 mL tube   | Falcon 50 mL high clarity conical centrifuge tube  | Corning falcon| 1| Can be substituted with generic. Must be sterile. |
| Sterivex | Sterivex-GP pressure filter unit, PES membrane| Millipore Sigma  | 3 | Cannot be substituted for this protocol.   |
| Sterivex/syringe caps     | Sterile luer caps  | McKesson| 6| Can be substituted with generic, must be sterile and individually packaged.  |
| 5 mL luer lock syringes| Luer lock disposable syringe | BD | 24  | Can be subsituted with generic. Must be sterile and luer lock.  |
| Label tape  | VWR general-purpose laboratory labeling tape   | VWR  | 1 | Can be substituted with generic. |
| Whirl-pak | Whirl-pak standard sample bags (4 oz. capacity)  | Nasco | 3   | Can be substituted with generic, must be sealed and sterile.    |
| 1000 μL pipette tips  | TipOne RPT filter tips 1000 μL | USA Scientific    | 6 | Can be subsituted with generic. Must be sterile and filtered. Must fit into the inlet of sterivex. |
| Kimwipes | Delicate task wipes | Kimtech  | 2 wipes| Can be substituted with generic. Must be lint-free. |
| Nitrile gloves | Powder free nitrile gloves  | Fisher Scientific | 2 pairs  | Can be subsituted with generic nitrile gloves. Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
| Field notebook| Durable, hardcover lab notebook | Generic  | 1        | Dedicated to fieldwork  |
| Writing utensils | Pens and sharpies|Generic|2| Not made of wood - must be able to be wiped down with bleach/EtOH. |
| **Chemicals** | |   |          |  |
| 100% molecular grade EtOH | 200 proof molecular biology grade ethanol| Fisher Scientific | 6000 μL  | Can be substituted with generic, must be 200 proof and molecular biology grade   |
| 70% EtOH  | Molecular biology grade ethanol  | 10 mL|   |  |
| 10% bleach  | Hypochlorite bleach  | Clorox  | 100 mL   | Remake every ~5 days as bleach decomposes quickly at 10% concentration. The majority is used in bottle/tube sterilization.|
| **Optional Equipment** | |   |          |  |
| Cooler |Hard or soft-sided cooler | Generic | 1 | Cooler capable of fitting all sample bags and sufficient ice to keep samples cool |
| Ice | Frozen water (not dry ice)  | Generic|  1 | Should be bagged if possible to reduce contamination, can be substituted with sufficient reusable ice packs |
| Fridge | 4 degrees Celsius refrigerator  | Generic  | 1  | Should be able to maintain ~4 degrees Celsius and large enough to fit samples (gravity bags or Nalgene bottles) before filtration|

## STANDARD OPERATING PROCEDURE


INSERT Net Tows Cruise Report















### Preparation

**Glove Sterilization:**
When sterilizing any equipment or filtering, sterile nitrile gloves must be used. Gloves directly from the box are not considered sterile. To sterilize, squirt 10% bleach solution from a squirt bottle onto a new pair of gloves and rub hands together, then squirt with EtOH to get rid of bleach residue. Nitrile gloves should be worn at all times during the sterilization, sampling, filtering, preservation, and storage steps.

**Bucket Sterilization:**

1. Create a 10% bleach solution directly in a bucket (4-6 L). Seal the lid carefully and shake for 2-3 minutes.
2. Empty the 10% bleach solution. Fill the carboy with 3-4 L of RO water and shake for 1-2 minutes. Repeat this RO wash step two more times (= 3 rinses in total).
9. Once complete, close the bucket with a lid, label, and seal with tape.

**Bottle Sterilization:**
Gravity bags can be filled directly from the sample water in situ; however, if you require an intermediate, then one sterile bottle is required for each sample and each field blank.

Bottle Sterilization Method (RO Available):

1. Create a 10% bleach solution in one of the buckets (6-10 L total, depending on needs).
2. Fill 4-6 bottles at a time with 10% bleach solution; fill to the top and seal with a lid. Allow to sit for 7 minutes, then flip the bottle upside down. Allow to sit for 7 more minutes.
3. Pour 10% bleach from these bottles into the next set of bottles or reuse bleach for further sterilization needs.
4. Each bottle needs to be rinsed with RO. Fill each Nalgene bottle with ~200 mL of RO, and then shake for 30-45 seconds. Repeat process 2x (= three rinses in total).
5. Shake out excess RO dumped (doesn’t need to be entirely dry), close it with the cap, and then wrap the top with parafilm to maintain sterility. Always wrap in the direction the cap tightens, so clockwise.

Bottle Sterilization Method (RO Not Available):

1. Complete Steps 1-3 from Bottle Sterilization Method (RO Available)
2. Close it with the cap, then wrap the top with parafilm to maintain sterility. **This shouldn’t be done more than 24 hours in advance of sampling.**
3. Once the CTD is on deck, take bleached 1 L Nalgene bottles and dispense ~250 ml of the sample from the Niskin into the bottle; close the lid and shake vigorously. Dump. This will rid the container of residual bleach. Repeat process 2x (= three rinses in total). Water must come from the same Niskin that will be the source of the actual sample; otherwise, there will be cross-contamination.

**Connector Preparation and Sterilization:**
To facilitate the connection between the gravity bag and sterivex, an additional adaptor may be required, depending on the gravity bag brand. Create an adaptor by cutting the PVC tubing into 4" pieces and then adding the hose barb adaptor to one end. These connectors can be sterilized in advance and stored in whirl-paks. They can also be reused, as long as they are sterilized between each sample. We recommend bringing sufficient connectors to avoid a sampling backlog.

Connector Sterilization:
1. Prepare a 10% bleach solution in one of the buckets (2 L). Then, grab another sterile bucket and fill it with RO water (2 L).
2. Soak the connectors in the bucket with bleach for 15 min; make sure the bleach makes it into the inside of the tubing.
5. Before transferring to the RO bucket, make sure to run bleach again through the tubing. Shake gently to remove any large bleach droplets before transferring to RO.
6. Soak the connector in the bucket with RO for 15 min; make sure the RO makes it into the inside of the tube.
7. Once sterilized, with sterilized gloves, pack the connectors into whirl-paks. You can fit multiple connectors into a whirl-pak for short-term storage.

**Filtering Space Preparation:**
* Locate a secure area out of direct sunlight to set up gravity bags. Use carabiners to hang.
* A water collection receptacle is required, whether this is a bucket, bin, or sink.
* Optional but encouraged: store items that can easily tip/fall in rough seas in an anchored container, such as a tupperware or crate, to prevent falling and contamination.
* Aliquot molecular grade EtOH into a 50mL Falcon tube - pipette from this when filling sterivex cartridges to avoid contaminating the stock EtOH bottle. 

**Field Sampling Records:**

When eDNA sampling in the field, there should be a corresponding record sheet or field notebook. On larger cruises where cruise CTD logs are kept after each cast, record the sample # in the logs in the corresponding Niskin row. Record additional information like the date, sample #, sample depth, cast #, filtering issues, etc., in your own records sheet or notebook.

On smaller cruises where no CTD logs are kept or water is sampled without a CTD, more detail is required in the record sheet. Record the date, sample #, site name, lat/long, cast #, depth, and any other associated notes (e.g., filtering issues, sampling device, cast deployment time).

### Sampling
This protocol is mainly designed for samples collected with Niskin bottles. The samples are expected to be discrete and sealed masses of water that can be transferred directly to a sterile gravity bag or a 1 L Nalgene bottle without contamination (typically from the spout/spigot). This protocol can also be used for samples collected by hand in situ.

**Method 1 (Preferred): Sample directly into the gravity bag**
1. Label a gravity bag with the station name, date, site, and Niskin #.
2. Fill the bag with ~30-50 mL of sample water, shake for 20-30 seconds, and dump. Complete this rinse step 3x to ensure bag sterility.
3. Collect water directly from the Niskin or bucket into the gravity bag, then shut it tightly. At this stage, overfilling the bag is okay, as you can let out excess before filtering.

**Note**: After collecting, water ideally needs to be filtered within 4 hours. Samples must be kept on ice in a cooler out of the sun or in a fridge (4˚C) if not filtered immediately. Denote storage duration on the record sheet.

**Method 2: Sample into a 1 L Nalgene bottle, then transfer to a gravity bag**
The gravity bags are often not easy to store, so if you need to move to a different location, collecting into sterile Nalgene bottles might be easier. 

1. Label the Nalgene bottle with the station name, date, site, and Niskin #.
2. Fill the sterile 1 L Nalgene bottle with water from the Niskin or bucket. Ensure you fill above the bottom of the bottle neck (= 1 L), as you want extra sample water volume to rinse the gravity bag.
3. After collecting, if you don’t have time to filter immediately, label and store bottles in the fridge or cooler with ice (4˚C) for up to 12 hours (>4 hours is not ideal). Denote time on the record sheet.
4. When you are prepared to filter, label the gravity bag with the station name, date, site, and Niskin #.
5. Next, fill the gravity bag with ~30-50 mL of sample water, shake for 20-30 seconds, and dump. Complete this rinse step 2-3x (pending water availability) to ensure bag sterility. 
6. Once rinsed, dump the sample from the 1 L Nalgene bottle into the gravity bag.

### Filtration

1. Take filled gravity bags to a pre-determined filtering station and secure bags 4+ feet above the floor with carabiners. Make sure the caps (i.e., gravity bag top and tubing cap) are still properly sealed.

Note: Multiple bags can be filtered simultaneously; in addition, a field blank should always be included at least every 50 samples.

2. Put on a sterile pair of dry gloves. Set out all your sealed eDNA gear on a flat, dry, clean surface, including your connectors, sterivex filters, caps, syringe, pipette, etc.
3. Untangle the tube from the gravity bag and allow the end to dangle into the catchment container.
4. Grab a whirl-pak with sterile connectors. Carefully open the whirl-pak and remove the connector without touching either end. 
5. Remove the plastic cap from the conical end of the gravity bag tubing and twist the sterile tubing connector on snugly. The tubing will be free-hanging, so ensure you protect the sterility of the connector.
6. Use a screwdriver/small key or other flat tool to twist the locking mechanism on the gravity bag so water flows freely. Release water until 1L is in the pouch and then re-cap/lock the tubing. 
7. Use binder clips or tape to secure the connector to the edge of the catchment container.
8. Repeat this process for other gravity bags.
9. Replace wet gloves and put on a sterile dry pair.
10. Carefully open the sterivex filter on one end. Do not throw away the wrapper, as the inside is sterile and will be used later. Label the sterivex with the sampling number.
11. While holding the gravity bag tubing skyward, twist the sterivex filter into place.
12. Resecure the tube to the side of the catchment container and point the sterivex into the bucket. Avoid crimping the tubing or touching the tip of the sterivex.
13. Repeat for all samples.
14. Twist the locking mechanism open and start the filtering process. Filtering 1 L takes on average 30-35 minutes. Take note of the time and potential contaminants.

Note: Stop filtering after 120 minutes (2 hours) even if less than 1 L has been filtered
Turbid samples may only filter ~500 mL. Note the estimated volume filtered. If <200 mL of water is filtered, consider using a second sterivex to filter more water.

### Sample Preservation

1. Once filtering is done, put on a new pair of sterile gloves and remove the sterivex. Place it in the wrapper it originated from for temporary safe-keeping.
2. Use a new, sterile 5 mL syringe filled with air to push all water out of the sterivex, inserting the syringe on the inlet end of the cartridge.
3. Then, add a new cap to the outlet end of the sterivex cartridge.
4. Using a 1000 μL pipette, gently push the tip into the sterivex inlet to make a seal (important!) and slowly add 1000 μL of 100% molecular grade EtOH into the sterivex filter. Repeat step with a new tip, so the total volume in the sterivex is 2000 μL.
5. Cap the sterivex inlet with a sterivex/syringe cap. Once sealed, shake the sterivex to ensure all sides of the filter material have been saturated with EtOH.
6. Ensure the previous sample number written on the sterivex is still visible. If not, redo.
7. Put the entire sealed cartridge into a small labeled whirl-pak. Place all sterivex from a single site (replicates or samples taken at different depths in a single Niskin rosette/CTD cast) into a single gallon plastic bag. Store in -20˚C freezer.

Note: Do not reuse gravity filter bags, unless it's for technical replicates. They should be disposed of after filtering is complete. Connector PVC tubing can be saved and resterilized.

### Storage

Store preserved samples in a -20˚C freezer for the duration of the cruise. When transporting preserved samples, the ideal condition is a cooler with ice packs so they remain below freezing. OME preserved samples are shipped (freezer to freezer) in under 24 hours and kept with ice packs at all times. 

Any storage issues should be noted. Samples **may** remain preserved if briefly thawed to refrigeration temperature (4˚C) and returned to freezing temperatures within 24 hours. 

### Quality Control

A field blank consisting of sterile RO water in a pre-filled and sealed (before fieldwork) 1 L bottle. Blanks should be filtered at the start and end of a cruise/fieldwork trip using a new gravity bag and sterile connector fittings. If more than 50 samples are collected on a cruise, an additional field blank is filtered every 50 samples. 

### Basic Troubleshooting Guide

**Issue 1:** Clogged filter

**Solution:** If a sterivex clogs prior to filtering 1 L (water no longer passes through), then denote the volume filtered and, when available, continue filtering through a new sterivex. Repeat until 1 L is filtered. Mark each additional sterivex, record additional sample names and notes, and denote volumes filtered for each in the field notebook.

**Issue 2:** Filtering is moving too slowly.

Closing and reopening the locking mechanism has been found to increase the flow rate when filtration has slowed. In addition, positive pressure to the bag can be applied to get the water flowing faster. If filtering exceeds 120 minutes (2 hours), stop filtering after 120 minutes (2 hours), even if less than 1 L has been filtered. Turbid samples may only filter ~500 mL. Note the estimated volume filtered. If <200 mL of water is filtered, consider using a second sterivex to filter more water.

**Issue 3:** Broken filter inlet or outlet

**Solution:** If broken during filtering, stop filtering, record volume filtered, and denote damage. Next, use parafilm and label tape to seal the broken outlet/inlet of the sterivex. Store in whirl-pak. The sample might be salvageable. 

## REFERENCES

## APPENDIX A: DATASHEETS
[Protocol Data Sheet](https://docs.google.com/spreadsheets/d/1MKNcWcW8v8AlEfASEV-uqE-QKrhblGvU/edit#gid=1853281061)
[Sterivex Diagram](https://github.com/marinednadude/NOAA-PMEL-OME_eDNA_Collection_Protocol_CTD/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_CTD_SterivexDiagram.png)  
