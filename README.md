# NERD (Near East Radiocarbon Dates)
![logo_small](https://user-images.githubusercontent.com/13691742/145385495-ea6e46d9-7ebe-4d28-8136-2a35aa8ea3ea.png)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5767862.svg)](https://doi.org/10.5281/zenodo.5767862)

#### Alessio Palmisano, Andrew Bevan, Dan Lawrence & Stephen Shennan 

The archive NERD provides a collation of 11,027 radiocarbon dates from 1023 archaeological sites in the Near East from the Late Pleistocene until the Late Holocene (15 - 1.5 cal. kya BP). These dates have been collected from existing online digital archives, and electronic and print original publications. This is an ongoing dataset that will be updated step by step with new published radiocarbon dates. 

![Fig1](https://user-images.githubusercontent.com/13691742/145239317-f63bc888-9899-431b-a1dd-a8304d39bf09.png)







The plot below show the Summed Probability Distribution (SPD) generated by using all the calibrated radiocarbon dates (in grey, n=11,027) and those ones from short-lived organic samples (in green, n=3,548).

![Fig2](https://user-images.githubusercontent.com/13691742/145239596-d94b649b-6725-4aca-9b6f-ba956d431dc4.png)



There are several caveats related to the present dataset as the original radiocarbon dates had an inhomogeneous quality of associated information which reflect the diversity of standards in the original sources. For instance, 87% of the dates have information about the sample material (e.g., seed, bone), but only 28% have the material taxa (e.g., Triticum dicoccum, Ovis, etc.).  






## Main Dataset NERD

The main dataset is to be found within /data/nerd.csv. The csv-file is encoded in ‘UTF-8’. The geographic coordinates are stored as unprojected LatLon coordinate system, WGS84 datum. 


| Datafield | Description 
| :-----------   | :----------------------- | 
| DateID (numeric) | unique identifier for the radiocarbon sample | 
| LabID (character) | unique identifier for the lab’s radiocarbon sample |
|OthLabID (character)| unique alternative identifier for the lab’s radiocarbon sample |
|Problems (character)| problems related to the radiocarbon sample (e.g. missing Lab Id, duplicated Lab Ids, etc.)|
|CRA (numeric)| radiocarbon concentration expressed in years before present (BP)|
|Error (numeric)| Standard error of radiocarbon date in years|
|DC13 (numeric)| d13C values of radiocarbon sample|
|Material (character)| material of the radiocarbon sample|
|Species (character)| species of the radiocarbon sample|
|SiteID (numeric)| unique identifier of the site from which the radiocarbon sample has been collected|
|SiteName (character)| name of archaeological site|
|SiteContext (character)| original archaeological context from which the radiocarbon sample was collected|
|SiteType (character)| type of archaeological site|
|Country (character)| country from which the radiocarbon sample was collected|
|Longitude (numeric)| WGS84 eastings|
|Latitude (numeric)| WGS84 northings|
|LocQual (character)| scale defining the accuracy of the spatial coordinates of radiocarbon samples|
|Source (character)| source from which the radiocarbon samples have been collected|
|Comment (character)| Comments about the issues reported in the field "Problems"|

#### Location Quality Key

A – exact coordinates of radiocarbon sample (centroid of the archaeological site from which was collected)

B- the radiocarbon sample is within a 2km radius’ buffer of the coordinates collected

C -the radiocarbon sample is within a 5km radius’ buffer of the coordinates collected

D- the radiocarbon sample is within a 10 km radius’ buffer of the coordinates collected

E- the radiocarbon sample is within a 20 km radius’ buffer of the coordinates collected


## Major contributing datasets/databases

The literature used to compile the present dataset can be found in the file References.txt. However, NERD benefitted from the following existing digital online archives:

* [ArAGATS Data Portal](https://aragats.gorgesapps.us/search?utf8=%E2%9C%93&t=Radiocarbon&c=code&d=asc)

* [BANADORA. Banque Nationale de Données Radiocarbonne pour l'Europe et le Proche Orient, Centre de Datation par le Radiocarbonne.](http://www.arar.mom.fr/banadora/) Lyon: CNRS.  

* Benz, M., 2014. [PPND - the Platform for Neolithic Radiocarbon Dates](https://www.exoriente.org/associated_projects/ppnd.php) 

* Böhner, U., and Schyle, D., 2006. [Radiocarbon CONTEXT database 2002-2006](http://context-database.uni-koeln.de/)

* [CalPal - The Cologne Radiocarbon Calibration & Palaeoclimate Research Package.](https://uni-koeln.academia.edu/BernhardWeninger/CalPal) Developed by Weninger, B., Jöris, O., and Danzeglocke, U.

* Hinz, M., Furholt, M., Müller, J., Raetzel-Fabian, D., Rinne, C.,  Sjögren, K. G., and Wotzka,H. P., 2012. [RADON - Radiocarbon dates online 2012. Central European database of 14C dates for the Neolithic and Early Bronze Age. Journal of Neolithic Archaeology, 14, 1-4](http://radon.ufg.uni-kiel.de/) 

* [IRPA/KIK. Royal Institute for Cultural Heritage web based Radiocarbon database.](http://c14.kikirpa.be/) Van Strydonck, M. and De Roock, E., 2011. Royal Institute for Cultural Heritage web-based radiocarbon database. Radiocarbon, 53(2), pp.367-370. 

* [ORAU. Oxford Radiocarbon Accelerator Unit online database.](https://c14.arch.ox.ac.uk/database/db.php) Oxford: University of Oxford.

* Reingruber, A., and Thissen, L., 2016. [The 14SEA Project. A 14C database for Southeast Europe and Anatolia (10,000–3000calBC).](http://www.14sea.org/2_dates.html)

* [TAY Project 14C sample Database](http://tayproject.org/C14searcheng.html) 


## Licence

The NERD dataset is made available under the [Creative Common License CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## How to cite
Palmisano, A., Bevan, A., Lawrence, D., & Shennan, S., 2021. "NERD: Near East Radiocarbon Dates", version 4.0 (8 December 2021): 
https://github.com/apalmisano82/NERD

## Case studies using NERD

* Lawrence, D., Palmisano, A., & Gruchy, M. W. de., 2021. [Collapse and continuity: A multi-proxy reconstruction of settlement organization and population trajectories in the Northern Fertile Crescent during the 4.2kya Rapid Climate Change event](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0244871). PLOS ONE, 16(1), e0244871.

* Palmisano, A., Woodbridge, J., Roberts, N., Bevan, A., Fyfe, R., Shennan, S., et al. 2019. [Holocene landscape dynamics and long-term population trends in the Levant.](https://doi.org/10.1177%2F0959683619826642) The Holocene,29(5), 708-727. 

* Palmisano, A., Lawrence, D., de Gruchy, M. W., Bevan, A., & Shennan, S., 2021. [Holocene regional population dynamics and climatic trends in the Near East: A first comparison using archaeo-demographic proxies.](https://doi.org/10.1016/j.quascirev.2020.106739) Quaternary Science Reviews, 252, 106739.

* Roberts, N., Woodbridge, J., Bevan, A., Palmisano, A., Shennan, S., & Asouti, E. 2018. [Human responses and non-responses to climatic variations during the last Glacial-Interglacial transition in the eastern Mediterranean.](https://doi.org/10.1016/j.quascirev.2017.09.011) Quaternary Science Reviews, 184, 47-67.

* Roberts, N., Woodbridge, J., Palmisano, A., Bevan, A., Fyfe, R., & Shennan, S. 2019. [Mediterranean landscape change during the Holocene: Synthesis, comparison and regional trends in population, land cover and climate.]( https://doi.org/10.1177%2F0959683619826697). The Holocene, 29(5), 923-937.

* Woodbridge, J., Roberts, C. N., Palmisano, A., Bevan, A., Shennan, S., Fyfe, R., et al. 2019. [Pollen-inferred regional vegetation patterns and demographic change in Southern Anatolia through the Holocene.](https://doi.org/10.1177%2F0959683619826635) The Holocene, 29(5),728-741. 

## Grants

The archive NERD was collated thanks to the following grants:

* [Changing the Face of The Mediterranean: Land cover and population since the advent of farming.](https://www.plymouth.ac.uk/research/centre-for-research-in-environment-and-society-ceres/changing-the-face-of-the-mediterranean-land-cover-and-population-since-the-advent-of-farming) Leverhulme Trust, grant number:
RPG-2015-031. Grant holders: Neil Roberts (PI), Andrew Bevan (Co-I), Ralph Fyfe (Co-I), & Stephen Shennan (Co-I). 

* [CLaSS - Climate, Landscape, Settlement and Society: Exploring Human-Environment Interaction in the Ancient Near East.](https://classerc.wordpress.com/the-project/) European Research Council, grant number: 802424. Grant holder: Dan Lawrence (PI).

* [Alexander von Humboldt Research Fellowship.](https://www.humboldt-foundation.de/en/apply/sponsorship-programmes/humboldt-research-fellowship) Grant holder: Alessio Palmisano.


![logos](https://user-images.githubusercontent.com/13691742/113167424-00930a80-9244-11eb-86cd-6833705cca42.png)


