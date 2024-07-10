# EstuarineExchangePaper
Namelists, postprocessing and analysis scripts for "Controls on Exchange through a Tidal Mixing Hotspot at an Estuary Constriction"

[![DOI](https://zenodo.org/badge/823764190.svg)](https://zenodo.org/doi/10.5281/zenodo.12712924)

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

### Other Analyses ###

Mixing_vs_advection-PtRoberts.ipynb, Mixing_vs_advection-mycross.ipynb : estimate impact of random walk on particle speeds through the mixing region, from SoG and from Vic Sill, respectively

Age_Analysis.ipynb : analyzing age of loops, efflux, reflux

Analyze_Lost_Particles.ipynb : collate statistics of "lost" particles

CalculateTides-Broader.ipynb : look at the tidal currents through the depth, maximum during the day and at other points

MeanVelocitiesAllMonths.ipynb : calculate the NEMO averaged velocities across the Point Roberts transect

### Figures ###

Figure 1: Maps-Cartopy.ipynb

Figure 2: a) Ariane_Locations.ipynb
          b) Maps-Cartopy.ipynb

Figure 4: a) & b) Similar to loadPSFCTD.ipynb
          c-j) PlotVENUSModelComparisons.ipynb

Figure 5: Transport-Analysis.ipynb

Figure 6: Ancillary.ipynb

Figure 7: FroudeFit.ipynb

Figure 8: FluxBySalt.ipynb

Figure 9: FluxCrossSections.ipynb

Figure 10: FluxCrossSections_Vic.ipynb

Figure 11: FluxCrossSections.ipynb

Figure 12: Final_Figure_FluxCrossSections.ipynb

Figure A1: BarotropicBaroclinicMeanderSaltFlux.ipynb
           BarotropicBaroclinicMeanderSaltFlux-Vic.ipynb
