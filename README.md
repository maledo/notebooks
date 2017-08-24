# notebooks

This repository contains differen [Jupyter notebooks](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) I created for my work.

## Aggregation

### Transmission
In the aggregation folder, my script for extracting [SciGrid data](http://www.scigrid.de/pages/downloads.html) (based on openstreetmap data) for Bavaria is published. It can be easily rewritten to extract and aggregate other regions, too.

### List of power plants
The German Bundesnetzagentur publishes a list of all german power plants. For my Bavarian [urbs](https://github.com/tum-ens/urbs) model, I extracted the conventional power plants from that list with the added script.

## Timeseries

### Hydro timeseries
The hydro timeseries used for the Bavarian [urbs](https://github.com/tum-ens/urbs) model is created with data from the [Bavarian Hydrological Service](http://www.gkd.bayern.de/fluesse/abfluss/karten/index.php?thema=gkd&rubrik=fluesse&produkt=wasserstand&gknr=0&sp=en) provided by the Bavarian Environmental Agency and the full load hours from the Energieatlas Bayern also from the Bavarian Environmental Agency, licensed via [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

### Load timeseries
The load curves are based on the ENTSO-E load timeseries downloaded from the [Open Power System Data Platform](https://data.open-power-system-data.org/time_series/). The timeseries is originally from the ENTSO-E transparency platform.
