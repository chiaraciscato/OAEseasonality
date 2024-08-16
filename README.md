## Impacts of Ocean Alkalinity Enhancement on the Seasonal Cycle of the CO<sub>2</sub> flux and ocean pCO<sub>2</sub> in European Waters in a low- and a high-emission scenario


A seasonal analysis was performed on five variables, with the objective of defining the impacts of Ocean Alkalinity Enhancement on their monthly (seasonal) cycle. The variables are listed below from drivers to outcome parameters:

- Alkalinity (μmol kg<sup>-1</sup>)
- pH
- Dissolved Inorganic Carbon (μmol kg<sup>-1</sup>)
- CO<sub>2</sub> flux (mol m<sup>-2</sup> yr<sup>-1</sup>)
- Ocean pCO<sub>2</sub> (µatm)

Two reference scenarios are used: SSP1-2.6 (low warming) and SSP3-7.0 (high warming).

The model domain is the European coastline (excluding the Mediterranean and the Baltic seas).

### Repository content

This repository contains three folders:

- the [scripts](scripts) folder contains three python scripts that process and plot: a geographical map of [OAE addition](scripts/OAEaddition), a latitudinal transect of the [North Sea](scripts/northSeaMap.ipynb), the seasonal analysis of [all five variables](scripts/process&plot.ipynb). 
- the [thesisMaterial](thesisMaterial) folder contains the MSc thesis report in its [latex](thesisMaterial/thesisReport) as well as [PDF](thesisMaterial/thesisReport.pdf) version, and the [thesis presentation](thesisMaterial/thesisPres.pdf) that showcased my results in the final discussion of my MSc programme.
- the [out](out) folder contains the final figures conceived to show the results.

### To keep in mind

The python scripts assume that the input data have already been sliced to the region of focus, namely the European coastline. The exact extremes are noted in the script that addresses the seasonal analysis of the variables. 

## Author

- [@chiaraciscato](https://github.com/chiaraciscato)

