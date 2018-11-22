# asteroid
For creating and analyzing an asteroid light curve from raw FITS data

[DataReduction.ipynb](DataReduction.ipynb) is where I calibrated my images, correcting for readout signal, dark current, and imperfections in the optical path.
[DataProcessing.ipynb](DataProcessing.ipynb) is where I turned my calibrated images into lists of the asteroid's apparent magnitudes, using the classes defined in [Analyis.py](Analyis.py) which are for storing and analyzing FITS files and sets of FITS files from a single night of observation pointing at the same field of view.
[LightCurve.ipynb](LightCurve.ipynb) is where I created the asteroid light curve, tried different rotational periods, and calculated the asteroid's primary axis ratio from the light curve amplitude.
