# Relationship Between Blue Whale Migration and Environmental Factors

## Authors

* Lyssa Hanson email: <ahanson2@uoregon.edu>
* Gage Doyle email: <gdoy@uoregon.edu>

### Summary

This project seeks to determine if whale movement along the California Coast have changed between 1999 and 2008, and if said changes are correlated to environmental factors like sea-surface temperature.

### Objective/Question

* Map the migration patterns in years 1999 & 2008.

* Has the migration patterns of Blue whales changed between 1999 and 2008?
  If so, by what distance?

* What is the average sea surface temperature of the migration sites.

* Has the average sea-surface temperatures of the sites changed between 1999-2008? If so, how much?

* If the migration sites have changed, what are the current water temperatures of the new sites, and how do they compare to the orignal temperatures of the 1999 sites? Are they similar/correlated?

* How do the current temperatures of the new sites compare to current temeratures at the original sites?

* Does sea surface temperature indicate any correlation to whale migration patterns?

* Other Environmental factors to consider?

### Package Requirements Include

* jupyter
* seaborn
* matplotlib
* pandas
* scikit-learn
* geopandas
* numpy
* shapely
* osmnx
* networkx
* rioxarray
* selenium
* bs4
* descartes
* momepy
* folium

 All required packeges can be installed using: `pip install requirements.txt`

### Planned methods/approach

1. Isolate the years of interest from both datasets

2. Calculate the mean water temperature for years of interest isolated by winter vs summer.

3. Locate whale movement and plot.

4. Create change map for temperature.

5. Find locations and cooresponding temperature changes.

6. Calculate whale displacement distance.

### Expected outcomes

We expect to see slight changes in migration patterns, perhaps to the west where deeper, cooler, water is located as average sea-surface temerature changes. We also expect to see minor temperature changes off the coast of California between these years. This year span is small so only minor changes are expected. However, if there is a trend, even if it is small we may expect this to continue. The new migration sites may have sea-surface temperatures similar to the original sites in 1993.

### Other relevant information

Add to as needed.

### References

Add to as needed.

### Dateset Citations

This project will use two main datasets, The Blue whales Eastern North Pacific 1993-2008 - Argos data, and the NOAA Global Surface Temperature Dataset (NOAAGlobalTemp).

#### Blue Whale Dataset Creditation

**Name** : Blue whales Eastern North Pacific 1993-2008 - Argos data

**License Type**: CC BY

**License Terms**: Creative Commons Attribution (CC BY)

**Citation**: Mate BR, Palacios DM, Irvine LM, Follett TM. 2019. Data from: Behavioural estimation of blue whale movements in the Northeast Pacific from state-space model analysis of satellite tracks. Movebank Data Repository. <https://www.doi.org/10.5441/001/1.5ph88fk2>

Bailey H, Mate BR, Palacios DM, Irvine L, Bograd SJ, Costa DP. 2009. Behavioural estimation of blue whale movements in the Northeast Pacific from state-space model analysis of satellite tracks. Endanger Species Res. 10(1):93-106. <https://doi.org/10.3354/esr00239>

Abrahms B, Hazen E, Aikens EO, Savoca MS, Goldbogen J, Bograd S, Jacox M, Irvine LM, Palacios DM, Mate BR. 2019. Memory and resource tracking drive basin-scale migrations. Proc Natl Acad Sci USA. 116(12):5582-5587. <https://doi.org/10.1073/pnas.1819031116>

Hazen EL, Palacios DM, Forney KA, Howell EA, Becker E, Hoover AL, Irvine L, DeAngelis M, Bograd SJ, Mate BR, et al. 2016. WhaleWatch: a dynamic management tool for predicting blue whale density in the California Current. J Appl Ecol. 54(5):1415-1428. <https://doi.org/10.1111/1365-2664.12820>

Irvine LM, Mate BR, Winsor MH, Palacios DM, Bograd SJ, Costa DP, Bailey H. 2014. Spatial and temporal occurrence of blue whales off the U.S. west coast, with implications for management. PLOS ONE. 9(7):e102959. <https://doi.org/10.1371/journal.pone.0102959>

Etnoyer P, Canny D, Mate BR, Morgan LE, Ortega-Ortiz JG, Nichols WJ. 2006. Sea-surface temperature gradients across blue whale and sea turtle foraging trajectories off the Baja California Peninsula, Mexico. Deep-Sea Res II. 53(3-4):340-358. <https://doi.org/10.1016/j.dsr2.2006.01.010>

Etnoyer P, Canny D, Mate B, Morgan L. 2004. Persistent pelagic habitats in the Baja California to Bering Sea (B2B) ecoregion. Oceanography. 17(1):90-101. <https://doi.org/10.5670/oceanog.2004.71>

Mate BR, Lagerquist BA, Calambokidis J. 1999. Movements of North Pacific blue whales during the feeding season off southern California and their southern fall migration. Mar Mammal Sci. 15(4):1246–1257. <https://doi.org/10.1111/j.1748-7692.1999.tb00888.x>\
***Principal Investigator Name*** : Daniel Palacios

#### NOAA Global Surface Temperature Dataset Citation

**Name**: Extended Reconstructed Sea Surface Temperature (ERSST), Version 4
ERSST v4

**License Type**: CC BY

**License Terms**: Creative Commons Attribution (CC BY)

**Citation**:  Boyin Huang, Viva F. Banzon, Eric Freeman, Jay Lawrimore, Wei Liu, Thomas C. Peterson, Thomas M. Smith, Peter W. Thorne, Scott D. Woodruff, and Huai-Min Zhang, 2015: Extended Reconstructed Sea Surface Temperature (ERSST), Version 4. 1999 & 2008 Subsets. NOAA National Centers for Environmental Information. doi:10.7289/V5KD1VVF 06/01/2024.


**Link** <https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.ncdc:C01585>

***Cited Authors***:	
Huang, Boyin
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Banzon, Viva F.
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Freeman, Eric
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Lawrimore, Jay
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Liu, Wei
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Peterson, Thomas C.
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Smith, Thomas M.
DOC/NOAA/NESDIS/STAR > Center for Satellite Applications and Research, NESDIS, NOAA, U.S. Department of Commerce

Thorne, Peter W.
NERSC > Nansen Environmental and Remote Sensing Centre

Woodruff, Scott D.
UCO/CIRES > Cooperative Institute for Research in Environmental Sciences, University of Colorado

Zhang, Huai-Min
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce


***Principal Investigators***:
Huang, Boyin
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

***Collaborators***:

Banzon, Viva F.
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Freeman, Eric
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Lawrimore, Jay
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Liu, Wei
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Peterson, Thomas C.
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

Smith, Thomas M.
DOC/NOAA/NESDIS/STAR > Center for Satellite Applications and Research, NESDIS, NOAA, U.S. Department of Commerce

Thorne, Peter W.
NERSC > Nansen Environmental and Remote Sensing Centre

Woodruff, Scott D.
UCO/CIRES > Cooperative Institute for Research in Environmental Sciences, University of Colorado

Zhang, Huai-Min
DOC/NOAA/NESDIS/NCEI > National Centers for Environmental Information, NESDIS, NOAA, U.S. Department of Commerce

***Publishers***
NOAA National Centers for Environmental Information
