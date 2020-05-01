# Molecular-gas-probe
First, I compute the rest frequency range with observed frequency and redshift. 
  H2O survey: 180344.164-184519.764MHz and 192870.964-197046.564MHz
  HCN J=2-1 survey:175829.94-179787.366MHz and 187802.406-191809.926MHz

Then, I found the theoretical lines in the range of 175~197GHz from Splatalogue, saved in molecule.xlsx(Sheet 1 shows the common molecule lines, sheet 2 shows all lines). I select the top 6 by the in CDMS intensity.

Do the data reduction using GILDAS/CLASS
Step1: do the summary of the observed sources.
Step2: combine the coincident bands.
Step3: average data from the same source and by the same telescope.
Step4: bin 200, draw the lines by 'draw molecule' and save them by 'hardcopy', there are some problems of the lines.
