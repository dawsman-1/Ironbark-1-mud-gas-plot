# Ironbark 1 mud gas plot
Visualisation of mud gas and other well data from the Ironbark-1 exploration well drilled/ operated by BP Developments Australia Pty Ltd in the Dampier Sub-basin, offshore Western Australia.

Plot has been created using the Plotly library, and are interactive (hover labels, zoom in/out, pan etc.)

All raw data and reports used are open-file and publicly available, and was downloaded from https://nopims.dmp.wa.gov.au/nopims

Interactive visualisation can be seen here: https://dawsman-1.github.io/Ironbark-1-mud-gas-plot/

## Dependencies
* pandas
* numpy
* lasio
* plotly

## Notes
1. Formation names, top and base depths were obtained from a list of mud gas samples in the Ironbark-1 Compositional Analysis Report, and are based on Isotube sample depths which may not correspond exactly to actual formation top/ base depths.

2. Ethene ratios were mined/ digitized from Figure 11 of the Ironbark-1 Natural Gas Characterization Interpretive Report, and therefore may not correspond to the exact values.

<br/>

#### Preview:

![alt text](https://github.com/dawsman-1/Ironbark-1-mud-gas-plot/blob/main/Data/Ironbark-1_plot_for_readme.png?raw=true)

<br/>

#### Ironbark-1 well schematic <I>(Ironbark-1 Initial Well Completion Report, p10):</I>

![alt text](https://github.com/dawsman-1/Ironbark-1-mud-gas-plot/blob/main/Data/Ironbark-1_well_schematic.png?raw=true)
