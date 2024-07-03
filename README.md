# EstuarineExchangePaper
Namelists, postprocessing and analysis scripts for "Controls on Exchange through a Tidal Mixing Hotspot at an Estuary Constriction"

### Ariane Runs ###

Namelists in directory Namelists see subdirectory names below.

From Victoria to Point Roberts and Gulf Island Transect (also to Puget and Discovery)
   Run forward
   Directory: FullSouth

To Point Roberts from Victoria Sill (also from Gulf Islands, Puget and Discovery)
   Run backward
   Directory: BackNorth

To Gulf Islands from Victoria Sill (also from Point Roberts, Puget and Discovery)
   Run backward
   Directory: InGIslands

From Point Roberts to Victoria Sill (also to Gulf Islands, Puget and Discovery)
   Run forward
   Directory: FullNorth

From Gulf Islands to Victoria Sill (also to Point Roberts, Puget and Discovery)
   Run forward
   Directory: SouthGIslands

To Victoria Sill from Point Roberts and Gulf Island Transect (also from Puget and Discovery)
   Run backward
   Directory: BackSouth

### Data Processing ###

Transport.ipynb : extracting the flux, age, position, salinity and temperature information from the individual Ariane files and storing it in csv files for analysis and plotting.

Transport-Analysis.ipynb : determining the phase shift to match the forward and backward fluxes.  Much preliminary analysis of the fluxes.  Also produces the transport figure. (Figure 4 in the revision)

CalculateDensity-Hindcast.ipynb : calculate the density difference between Point Roberts transect and Victoria Sill

CalculateTides.ipynb : calculate the tides in Boundary Pass

CalculateSSH.ipynb : calculate the SSH at Neah Bay

CalculateWind.ipynb : calculate the Sand Head winds

SoGRunoff.ipynb : calculate the river flux into the SoG

### Figures ###

Figure 4: Transport-Analysis.ipynb
