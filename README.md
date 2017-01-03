# Pmag_Seminar

Possible papers for Spring 2017:

Charles Aubourg, Jean-Pierre Pozzi, and Myriam Kars
Burial, claystones remagnetization and some consequences for magnetostratigraphy
Geological Society, London, Special Publications, 371:181-188, first published on June 27, 2012, doi:10.1144/SP371.4
Abstract Full text Full text (PDF)




## Fall 2016 Group Meeting and Pmag Seminar

[Main PmagPy repo](https://github.com/PmagPy/PmagPy)

[PmagPy in Python 3](https://github.com/Caoimhinmg/PmagPy)

| Meeting Date | Reading/Prep |
|--------------|--------------|
|09/02/16| [PmagPy Cookbook](https://earthref.org/PmagPy/cookbook/)	Chaps. 1, 4, 7 and 8; Put in pull request on the [Cookbook Repository](https://github.com/PmagPy/PmagPy-Cookbook/blob/gh-pages/PmagPy.tex). Read [Essentials Chapter 1](https://earthref.org/MagIC/books/Tauxe/Essentials/WebBook3ch1.html) and complete [essentials_ch_1 problem set](https://github.com/Swanson-Hysell-Group/Pmag_Seminar/blob/master/Notebooks/essentials_ch_1_template.ipynb); download and run these Jupyter notebooks: https://github.com/PmagPy/2016_Tauxe-et-al_PmagPy_Notebooks
|09/09/16| Read [Essentials Chapter 2: The Geomagnetic Field](https://earthref.org/MagIC/books/Tauxe/Essentials/WebBook3ch1.html) and complete Chapter 2 problems 1b, 2b and 3. Dig into the guts of: ipmag.igrf, pmag.doigrf and pmag.magsyn. Compare 5 ipmag.igrf calculations with calculations using: https://github.com/cmweiss/geomag and [online calculator](http://www.ngdc.noaa.gov/geomag-web/#igrfwmm). Check IGRF-12 coefficients in pmag.get_igrf12. Improve docstrings in ipmag.igrf, pmag.doigrf and pmag.magsyn. Make sure functions are consistent within mk_sam_utilities.py.|
|09/16/16| Read [Essentials Chapter 9](https://earthref.org/MagIC/books/Tauxe/Essentials/WebBook3ch9.html). Have a look at [Essentials Chapter 11](https://earthref.org/MagIC/books/Tauxe/Essentials/WebBook3ch11.html). Use pmag_gui (link to executable [here](https://github.com/PmagPy/PmagPy-Standalone-OSX/releases/tag/1.1.1) or you can launch it at the command line) to convert PI47-.sam to MagIC and then using demag_gui to make the fits. Record the Fisher mean you get for the LT and HT fits and we will compare. |
|09/23/16| Read [Morgan (1971)](http://www.nature.com/nature/journal/v230/n5288/abs/230042a0.html) and [Tarduno et al. (2003)](http://science.sciencemag.org/content/301/5636/1064) and [Tarduno et al. (2009)](http://science.sciencemag.org/content/324/5923/50) Special Seminar: Richard Gordon (Rice University) *Origin of the Hawaiian-Emperor Bend: New Evidence* Abstract: Two main explanations have been proposed for the origin of the Hawaiian-Emperor Bend (HEB): (1)  that it records a change in motion of the Pacific plate relative to a stationary Hawaiian plume [Morgan, 1971];  (2) that Pacific plate motion has been uniform but the HEB records a change from rapid (>40 mm/yr) southward motion of the Hawaiian plume while the Emperor chain was formed to a stationary plume while the Hawaiian chain was formed [Tarduno et al., 2003]. Recent work, which will be reviewed in this talk, invalidates prior studies that inferred significant rates of motion between hotspots since the time of the HEB.  Nominal rates of motion are 2 to 6 mm/yr with a lower bound of zero and upper bounds of 8−13 mm/yr (95% c. l.).  In this context, Hawaiian plume drift as great as 40 mm/yr before 50 Ma B.P. seems unlikely. To infer motion of the Hawaiian hotspot relative to the mantle from paleomagnetic data one must ignore true polar wander (TPW), but TPW is too big to ignore and is occurring today—it is an important part of explaining the apparent polar wander (APW) of the Pacific and other plates.  New evidence, which will be detailed in this talk, shows that the Hawaiian hotspot was fixed in latitude during formation of most, if not all, of the Emperor seamount chain, in contradiction to the southward motion found by Tarduno et al. [2003]. Revised timing and age-dating of the HEB (now ~50 Ma) implies that the change in plate motion coincides with a change in Pacific-Farallon motion and other circum-Pacific tectonic events.   Barkhausen et al [2013] show that the Pacific-Farallon spreading rate doubles between ~50 Ma and ~40 Ma coincident with the acceleration of the Pacific plate from the HEB to the Hawaiian trend and an increasing propagation rate along that trend. We conclude that current evidence still favors W. J. Morgan’s original explanation for the HEB: that it records a change in Pacific plate motion relative to the deep mantle|
|09/30/16| Fluxgate in action |
|10/07/16| Chapter 7 of Essentials (Chapter 3 and 4 as background). Tackle problems and present to one another: Chapter 7 problem 1 (Oliver, Nick), problem 2 (TK, Sarah), problem 3 (Yuem, Courtney), problem 4 (Luke) |
|10/14/16| Chapters 11 and 12 of Essentials. Download and execute the example PmagPy notebooks in this repository:  https://github.com/PmagPy/2016_Tauxe-et-al_PmagPy_Notebooks. Make your own notebook that deals with some real data and do some Fisher statistics (and go beyond Fisher statistics) on it. Nick is out of town at the meeting---given that he authored this notebook (https://github.com/PmagPy/2016_Tauxe-et-al_PmagPy_Notebooks/blob/master/Additional_PmagPy_Examples.ipynb), let's have Luke direct the show and everyone can present what data they tackled. |
|10/21/16| Continue to work with datasets individually in Jupyter notebooks; each person can walk through their notebook and point out useful functions. Take a look through ipmag/pmag code and look for places where documentation, etc. can be improved---if you see something, say something. Download the 2016 Teel basalts notebook (https://github.com/Swanson-Hysell-Group/2016_Teel_Basalts/tree/master/Code) or view it statically (https://nbviewer.jupyter.org/github/Swanson-Hysell-Group/2016_Teel_Basalts/blob/master/Code/Teel_Formation_pmag.ipynb) as a reference for working with real data. For anyone wanting to tackle this: look into implementing parametric bootstrap option per Sarah's request (https://github.com/PmagPy/PmagPy/issues/79).|
|10/28/16| |
|11/04/16| |
|11/11/16| |
|11/18/16| |
|11/25/16| Thanksgiving |
|12/02/16| |
|12/09/16| AGU Practice Presentations |
