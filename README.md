# Data underlying model of grey seal/cod/herring dynamics in the Southern Gulf of St. Lawrence (sGSL)

Rossi, S.P., Cox, S.P., Benoît, H.P. 2024. Absence of predator control increases cod extirpation risk in a Northwest Atlantic ecosystem: inference from multispecies modelling. *Marine Ecology Progress Series*.

Preprint: https://doi.org/10.48550/arXiv.2311.06521

## Grey seal data

### Survey/hunting data (Hammill et al. 2017)

`seal-pup-production-gulf.csv` - Pup production for the Gulf of St. Lawrence herd (1960-2016)

`seal-pup-production-shelf.csv` - Pup production for the Scotian Shelf herd (1960-2016)

`seal-removals-gulf.csv` - Removals from the Gulf of St. Lawrence herd (1960-2016)

`seal-removals-shelf.csv` - Removals from the Scotian Shelf herd (1960-2016)

`seal-reproductive.csv` - Reproductive status of females from Gulf of St. Lawrence herd (1969-2017)

`seal-ice-surival.csv` - Proportion of pups from Gulf of St. Lawrence herd surviving ice-related mortality events (1960-2016)

`seal-foraging-effort.csv` - Proportion of grey seals foraging near sGSL cod

### Bioenergetic/diet data (Benoît and Rail, 2016)

`seal-body-mass-monthly-male.csv` - Monthly male body mass (kg)

`seal-body-mass-monthly-female.csv` - Monthly female body mass (kg)

`seal-diet-herring-by-size.csv` - Lengths of herring consumed by grey seals (cm)

## Atlantic cod data

### Fishery/survey data (Swain et al. 2019)

`cod-catch.csv` - Commercial catch (tonnes; 1950-2018)

`cod-survey-indices.csv` - Survey indices (1971-2018)

`cod-age-composition.dat` - Age-composition, weight-at-age (kg), and maturity-at-age (1950-2018)

`cod-age-length-key.Rdata` - Age-length key contained within R object `rv.res.list` (1971-2018)

### Bioenergetic/diet data (Benoît and Rail, 2016)

`cod-occupied-temperature.csv` - Mean temperature (°C) occupied by cod longer than 30 cm

`cod-stomach-mass-pars.csv` - Fitted linear model for calculating stomach content mass

`cod-diet-30-44-proportion herring.csv` - Proportional contribution of herring to cod diet for cod of size 30-44 cm (digitized from Figure 15 in Benoît and Rail 2016)

`cod-diet-45-59-proportion herring.csv` - Proportional contribution of herring to cod diet for cod of size 45-59 cm (digitized from Figure 15 in Benoît and Rail 2016) 

`cod-diet-60-plus-proportion herring.csv` - Proportional contribution of herring to cod diet for cod of size 60+ cm (digitized from Figure 15 in Benoît and Rail 2016) 

## Atlantic herring data

### Data from previous sampling regime (1971-1981; Cleary 1982)

`herring-catch-1971-1981.csv` - Commercial catch (tonnes)

`herring-catch-proportions-1971-1981.csv` - Proportion of commercial catch taken from spring and fall spawners

`herring-biomass-4plus-1971-1981.csv` - Biomass of herring aged 4 years and older (tonnes)

`herring-spring-age-composition-1971-1981.csv` - Age-composition of spring spawners

`herring-fall-age-composition-1971-1981.csv` - Age-composition of fall spawners

`herring-spring-weight-at-age-1971-1981.csv` - Weight-at-age of spring spawners (kg; ages 1-11)

`herring-fall-weight-at-age-1971-1981.csv` - Weight-at-age of fall spawners (kg; ages 1-11)

### Data from current era (1978-2019; Rolland 2022)

`herring-spring-catch-1978-2019.csv` - Commercial catch of spring spawners

`herring-spring-survey-indices-1978-2019.dat` - Survey indices for spring spawners

`herring-spring-age-composition-1978-2019.dat` - Age-composition, weight-at-age, and maturity-at-age for spring spawners

`herring-fall-catch-1978-2019.csv` - Commercial catch of fall spawners

`herring-fall-survey-indices-1978-2019.dat` - Survey indices for fall spawners

`herring-fall-age-composition-1978-2019.dat` - Age-composition, weight-at-age, and maturity-at-age for fall spawners

`herring-age-length-key.Rdata` - Age-length key contained within R object `alk` (Provided by DFO)

## References

Benoît, H.P., and Rail, J.-F. 2016. Principal predators and consumption of juvenile and adult Atlantic Herring (Clupea harengus) in the southern Gulf of St. Lawrence. DFO Can. Sci. Advis. Sec. Res. Doc. 2016/065. viii + 42 p. https://publications.gc.ca/collections/collection_2016/mpo-dfo/Fs70-5-2016-065-eng.pdf

Cleary, L., 1982. Assessment of 4T Herring Stock. CAFSAC Res. Doc. 82/47. https://publications.gc.ca/collections/collection_2019/mpo-dfo/Fs70-8-82-47-eng.pdf

Hammill, M.O., den Heyer, C.E., Bowen, W.D., and Lang, S.L.C. 2017. Grey Seal Population
Trends in Canadian Waters, 1960-2016 and harvest advice. DFO Can. Sci. Advis. Sec. Res.
Doc. 2017/052. v + 30 p. https://waves-vagues.dfo-mpo.gc.ca/library-bibliotheque/40643542.pdf

Rolland, N., Turcotte, F., McDermid, J.L., DeJong, R.A., and Landry, L. 2022. Assessment of
the NAFO Division 4TVn southern Gulf of St. Lawrence Atlantic Herring (Clupea harengus)
in 2020-2021. DFO Can. Sci. Advis. Sec. Res. Doc. 2022/068. xii + 142 p. https://publications.gc.ca/collections/collection_2023/mpo-dfo/fs70-5/Fs70-5-2022-068-eng.pdf

Swain, D.P., Ricard, D., Rolland, N., and Aubry, É. 2019. Assessment of the southern Gulf of St. Lawrence Atlantic Cod (Gadus morhua) stock of NAFO Div. 4T and 4Vn (November to
April), March 2019. DFO Can. Sci. Advis. Sec. Res. Doc. 2019/038. iv + 105 p. https://waves-vagues.dfo-mpo.gc.ca/library-bibliotheque/40805542.pdf











