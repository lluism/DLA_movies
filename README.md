## DLA_movies
# Composite quasar and damped Lyman alpha system spectra - movies

  This repositori is linked to our paper "The mean metal-line absorption spectrum of DLAs in BOSS", Mas-Ribas et al. (2016/17)
It is created for illustrative purposes. Here I briefly describe the make-off for the movies but, please, 
check the article for detailed explanations.

  Feel free to use the movies for your own scientific purposes, and let me know if you want to know more about this, or 
have questions, comments, etc. "lluismasribas [AT] gmail [DOT] com "


  The repositori contains 2 movies displaying how the weighted mean spectrum of the quasars and DLAs evolves when 
adding more and more spectra to the calculation. We use the DLA catalog made by Pasquier Noterdaeme, who used the 
data of the Data Release 12 from the BOSS/SDSS_III collaboration.

Here some webbs and related references:
http://www2.iap.fr/users/noterdae/
http://www.sdss.org/dr12/algorithms/boss-dr12-quasar-catalog/
http://adsabs.harvard.edu/abs/2013AJ....145...10D
http://adsabs.harvard.edu/abs/2017A%26A...597A..79P
http://adsabs.harvard.edu/abs/2011AJ....142...72E


  Several scientifico-technical points:
* Before playing the video, you will see one red and one black spectra. This are 1, and the average of 2 spectra, respectively.
* Once running, the red spectra always show the "last frame", so you can see what is changing at every step.
* the number of systems included goes from 1 to 10, adding one spectra every time. From there, the evolution is quadratic, i.e., 
  16, 25, 36, 49, etc.
* I stop the video at ~25000 spectra, where further evolution is small.

* For this calculation, I consider our "total sample" in the article, containing most of the spectra in the overall catalog. 
* I applied some corrections for outliers, the mean absorption of the Lya forest, possible Lyb contamination, etc. 
* For computational-speed reasons, I performed a simple linear interpolation instead of our detailed flux-rebining. 
* For the DLA spectrum, I indicated most of the metal lines considered in the article, but you might find a few more.

Hope you like them!
Lluis
