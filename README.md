# Modeling Signals from Distant Emissions

Presenting data and programs (codes) used to evaluate astronomical data, primarily object emissions and associated redshifts.

`Presentation.pdf` --> can be used as a lecture aid for science teachers interested in presenting some of the problems students will encounter if one decides to transform data into another metric or into a form without a metric. This presentation aid can perhaps be used within an "hour" lecture; free to use without any monetary claim by MLS or AA.

`Supernova` --> Data and programs for modeling using supernovae type Ia (SNe Ia) data. One large data set is stored here.  These are the 1701 SNe Ia from Brout et al. 2022. The distance mag data are taken from the set used by Brout and the D_L and expansion factor data are calculated by us using the equations, 1,2,3,4, listed in section "2.2 Data preparation" of the manuscript.

Every evaluation presents several statistic calculations. First is the typical r^2 correlation, second is a version of the chi^2 calculation as commonly performed by astronomers (see Riess et al. 1998). Third - calculations of the values of the Bayesian Information Criteria (BIC). It is observed that the BIC test is not really very useful for comparing unrelated models with the SNe Ia data. Specifically, the BIC values calculated of the Einstein-DeSitter model variants do not reflect the relative failure of these models compared to models based on the Friedmann-Lemaitre-Robertson-Walker (FLRW) approximation, most which appear when plotted to better fit the SNe Ia data. Finally, calculations of the F-statistic are coded. The is a variant of the classic r^2 correlation but values increase dramatically with better correlation and more data and this statistic seems best for model evaluation.
