# KM-NMIBC
See https://stevenmonda.github.io/KM-NMIBC/ for the HTML preview.

Code-only share; data files are not included but obtained digitizing of referenced published swimmer plots and KM curve.

Plot Digitizer Used for Swimmer Plot Digitization and Reconstruct KM Pre-processing: https://plotdigitizer.com/

ReconstructKM ran within R: https://cran.r-project.org/web/packages/reconstructKM/index.html

IPDfromKM ran through MD Anderson hosted shinyapp: https://biostatistics.mdanderson.org/shinyapps/IPDfromKM/

Data Dictionary: 

event: defined per trial as high-grade urothelial cancer or distant recurrence throughout

survtime: time since therapy start to censoring or event 

crtime: time since therapy start to CR (this is the first cystoscopy, scheduled at 3 months and usually within a few weeks of this, except when reinduction is allowed)

timesincecr: time since cr was achieved to survival event, functionally survtime minus crtime

NAR: number at risk
