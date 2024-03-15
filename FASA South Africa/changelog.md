# Changelog - AIRAC 2405
## Enhancements
- [x] updated the TopSky Plugin to 2.5 beta 7
- [x] The entire RSA airspace has been redrawn in TopSky maps. All the sectors are now rendered based on the ASD zoom levels, This allows us to declutter the ASD.
- [x] All the significant RNAV waypoints are now drawn through TopSky Maps and are rendered based on ASD zoom levels. 
- [x] All the RNAV GNSS and RNP initial fixes can now be toggled through TopSky Maps.
- [x] The Lower levels of all the Class C Controlled airspace are displayed through TopSky Maps and are rendered based on ASD zoom level. 
- [x] LASS (Lowveld Information Military Airspace) will now only display during the hours of service. Otherwise the Sector falls under FAJA North ACC.
- [X] Reworked the track labels to more accurately represent the IRL TopSky ATM track Labels. More information on the function of the tags to follow in the eAIP.
- [X] Reworked the Symbology to now closely emulate the IRL ASD.
- [X] Cleaned up the runway approach lines. They are now represented with a single solid gray line. With a marker at 10 miles and a marker at 5 miles.
- [X] Reworked the AIW (Airspace Infringement Warnings) prediction times to help performance. 
- [X] Reworked the MTCD (Medium Term Conflict Detection) prediction time to help performance and remove superfluous warnings. 
- [X] Reworked the SAP (Segregated Area Probe). NOTE: You will need to have the specific TSA airspace toggled for the system to work.
- [X] Displays MODE S DAPs in track label with "@" prefix.
- [X] Implemented ISAsure plugin to accurately calculate Mach and IAS in the track label. 
- [X] Changed the default number of history dots to 5.
- [X] Fixed PDCs and simplified format.
- [X] Added more CPDLC freetext message options.
- [x] Removes the Sector Inbound and Sector Exit list and replaces them with the TopSky Sector List. Informed, Concerned and Redundant tracks can be toggled through the plugin global menu.
- [x] Reconfigured the departure list to implement the Initial Climb and vFPC plugin.
- [x] Adds runway closures to FACT and FAOR through the Ground Radar Plugin. Runways will display as closed on the Ground Radar depending on the selected runways. 
- [x] Adds togglable Taxiway restrictions to FAOR for A380 / B747-800 to FAOR.

## Bugfixes
- [x] All the incorrectly drawn airspace has been removed.
- [x] Removed the FACT RNAV fixes and SIDS that were rendering through Euroscope and TopSky Maps. 
- [X] Removed superfluous CPDLC stations.