This project uses four models to generate a plot of the lightcurve for specified parameers. The aim is to understand the dependencies of each model and compare them.

# Models
## BoxFit

Described in [Hendrik van Eerten, Alexander van der Horst, and Andrew MacFadyen. Gamma-ray burst afterglow broadband fitting based directly on hydrodynamics simulations. The Astrophysical Journal, 749(1):44, mar 2012.](https://arxiv.org/abs/1110.5089), and can be downloaded [here](https://cosmo.nyu.edu/afterglowlibrary/boxfit2011.html) as well as the box files. 
For the installation, it is recommended to follow the [user guide](https://cosmo.nyu.edu/afterglowlibrary/boxfitdatav2/boxfitguidev2.pdf) made by the author. 
Once it is installed and running, the outputdirectory (hereafter called 'boxfitoutput') should contain the following three files: 'boxfitsettings.txt' where the parameters are specified, 'lightcurve.txt' the output data of boxfit when it is asked to generate a lightcurve, 'spectrum.txt' the equivalent for a spectrum.

## Afterglowpy