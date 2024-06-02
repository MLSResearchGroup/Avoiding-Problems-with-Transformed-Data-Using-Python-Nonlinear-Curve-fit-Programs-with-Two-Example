# Modeling Signals from Distant Emissions

Presenting data and programs (codes) used to evaluate astronomical data, primarily object emissions, supernova type Ia, and associated redshifts.

`Presentation.pdf` --> Can be used as a lecture aid for science teachers interested in presenting some of the problems students will encounter if deciding to transform data into another metric or into a form without a metric. This presentation aid can perhaps be used within a one hour lecture; free to use without any monetary claim by MLS or AA.

`Supernova` --> Data and programs for modeling using supernovae type Ia (SNe Ia) data. One large data set is stored here which are the 1701 SNe Ia from Brout et al. 2022. The distance mag (\mu) and redshift (z) data are taken from the set presented by Brout et al. 2022 Astrophysical Journal, Vol. 938, p. 110. The D_L and expansion factor data are calculated from equations, 1,2,3,4, listed in section "2.2 Data preparation" of the manuscript, using an EXCEL spreadsheet.

Every evaluation presents several statistic calculations. First is the typical r^2 correlation, second is a version of the chi^2 calculation as commonly performed by astronomers (see Riess et al. 1998 AJ Vol. 116 p. 1009-1038). Third - calculations of the values of the Bayesian Information Criteria (BIC), fourth, the F-test which is a rarely used, statistical test which is very sensitive to correlation. It is observed that the BIC test is not really very useful for comparing unrelated models with the SNe Ia data and the F-test present the most useful results. Specifically, the BIC values calculated for the Einstein-DeSitter model variants do not reflect the relative failure of these models compared to models based on the Friedmann-Lemaitre-Robertson-Walker (FLRW) approximation, most which appear when plotted to better fit the SNe Ia data. The F-statistic values increase dramatically with better correlation and more data, this statistic seems best for model evaluation of SNe Ia data.
