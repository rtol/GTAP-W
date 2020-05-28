=========================================================================================================
"The GTAP-W Model: Accounting for Water Use in Agriculture”

Alvaro Calzadilla (a,*), Katrin Rehdanz (a,b) and Richard S.J. Tol (c,d,e,f)

(a) Kiel Institute for the World Economy, Kiel, Germany
(b) Christian-Albrechts-University of Kiel, Department of Economics, Kiel, Germany
(c) Economic and Social Research Institute, Dublin, Ireland
(d) Institute for Environmental Studies, Vrije Universiteit, Amsterdam, The Netherlands
(e) Department of Spatial Economics, Vrije Universiteit, Amsterdam, The Netherlands
(f) Department of Economics, Trinity College, Dublin, Ireland
(*) Corresponding author: Kiel Institute for the World Economy, Hindenburgufer 66, 24105 Kiel, Germany.
    Tel.: 49 431 8814 401; fax: 49 431 8814 500. E-mail address: alvaro.calzadilla@ifw-kiel.de
=========================================================================================================

This model was used in https://www.sciencedirect.com/science/article/pii/S0022169409007902, https://onlinelibrary.wiley.com/doi/full/10.1111/j.1574-0862.2010.00516.x and https://link.springer.com/article/10.1007/s10584-013-0822-4

==================
Files description:
==================
- “SplitLand.tab” TABLO file to split "land" into "PsLand", "RfLand", "Lnd" and "Wtr" 
- “SplitLand.sti” Stored-input file to split "land" into "PsLand", "RfLand", "Lnd" and "Wtr"
- “extradata.har” Shares to split land and new elasticities
- “Gtap-Water.tab” GTAP-W code
- “Gtap-Water.sti” Stores-input file to run GTAP-W
- “basedata.har” GTAP-W database
- “default.prm” GTAP-W parameters
- “sets.har” GTAP-W sets
- “Efficiency S1.cmf” Shocks for the water-scarce developing regions scenario
- “Efficiency S2.cmf” Shocks for the water-scarce regions scenario
- “Efficiency S3.cmf” Shocks for the all regions scenario


=====================================
To split land using different shares:
=====================================

1. Replace your shares in extradata.har

2. Run normally SplitLand.tab using SplitLand.sti to update basedata.har, default.prm and sets.har


==========================
To carry out a simulation:
==========================

1. Run gtap-water-tab from gtap-water.sti

2. Use the provided scenarios (*.cmf)
