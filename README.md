# StQTL_2sGenGPS
# Temporal quantitative trait loci analysis and causal inference unveils novel genetic drivers for the progression in neurodegenerative disease
Junfeng Luo, Hao Wu, for the Alzheimer’s Disease Neuroimaging Initiative, Ganqiang Liu\*

StQTL_2sGenGPS (Stationary temporal quantitative trait locus and two-stage genetic Granger temporal causality study) includes two novel multi-omics or multi-modal data integrative analysis frameworks (StQTL and 2sGenGPS) to identify temporal eQTLs (teQTLs) in genome-wide scale and unveil dynamic eQTLs exhibiting significant variation over time for stationary longitudinal gene expressions in longitudinal cohort studies (StQTL), and inferring temporal causality associations between longitudinal gene expression and longitudinal phenotypes using teQTLs in biomedical applications.


Overview of StQTL_2sGenGPS. \
<sup>Figure below shows the schematic of the St-QTL and 2sGen-GPS approaches. See manuscript 'Temporal quantitative trait loci analysis and causal inference unveils novel genetic drivers for the progression in neurodegenerative disease' for the illustration of StQTL_2sGenGPS. <sup>

![Schematic of the St-QTL and 2sGen-GPS approaches](https://github.com/sixguns1984/StQTL_2sGenGPS/blob/main/workflow.png)


## Files
*StQTL_main.py*: Example for StQTL analysis\
*StQTL.py*: Componets of the StQTL\
*teQTL_powertest_main.py*: Example for power test of significant teQTLs\
*teQTL_powertest.py*: Componets of power test for significant teQTLs\
*temporal_trait_adf_test.py*: Example of Augmented Dickey-Fuller (ADF) unit root test\
*twosGen_GPS_main.py*: Example for two stage Genetic Granger Temporal Causality Study\
*twosGen_GPS.py*: Componets of the 2sGen-GPS\
*prepare.py*: Componets of data preprocess for StQTL and 2sGen-GPS analysis\
*poly_regression_main.py*: Example for teQTL analysis using linear regression or cubic polynomial regression\
*polynomial_regression.py*: Componets of the teQTL based on polynomial regression model in tensor\
*AR1_main.py*: Example for teQTL analysis using first order Auto Regression\
*AR1.py*: Componets of teQTL analysis using first order Auto Regression\ 
*./StQTL_2sGenGPS/example*: Example data for StQTL_2sGenGPS


\* Correspondence author
