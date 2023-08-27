# Summer Research

a complimation of code that I wrote this summer~
<hr>

### AGN_dispersion.ipynb

<b>AGN_dispersion.ipynb</b> is a program from ETC_grism, modified to allow for the dispersion of multiple point sources (AGN). This program was originally developed for CASTOR, a proposed Canadian, UV, U, and G band space telescope. However this program would not be useful using real data because CASTOR is slitless, making dispersing <i>all</i> the light that comes through pointless. It is still a cool program though!  

### fake_spectra.ipynb

<b>fake_spectra.ipynb</b> is a better version of <b>learning.ipynb</b> so feel free to ignore that file :D
The inputs for the full width at half max of the Magnesium II and Calcium IV emission lines were in scientific notation, just a heads up in case you try to print the values. Also, the amplitude of all the emission lines is divided by 10 000, to properly scale to the sample data!

sample imputs:
###### all values in kilo-electronvolts or keV
| Parameter    | Arguement |
| -------- | ------- |
| Mg II Amplitude | 14.725 |
| Mg II FWHM | 5.3225560120812084474<b>e</b>-05 |
| Mg II Position | 0.004429984758667271|
|Calcium IV Amplitude | 25.291 |
|Calcium IV FWHM | 7.40432275000806<b>e</b>-05|
|Calcium IV Position | 0.008003834482408703 |
|Lyman-alpha Amplitude | 100.0 |
|Lyman-alpha FWHM| 0.000163269701214103012|
|Lyman-alpha Position| 0.10198836726512972|

### learning.ipynb

<b>learning.ipynb</b>, <i>which i will rename,</i>  is a program used to generate fake spectra emission lines, specifically AGN emission lines.


