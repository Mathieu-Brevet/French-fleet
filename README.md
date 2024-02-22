
## French Fleet Description

This project aims to build a tool allowing to classify a followed set of fishing vessels into different functional fishing strategies. We will work first on the fishing vessels in the Bay of Biscay from 2000 to 2022, as a case study. Classification of vessels ("Classification_fleet.qmd" file) is performed by considering the yearly activity of each vessel (a vessel could therefore change of fleet among years), i.e. the species targeted, fishing engines, fishing zones, economic activity, distribution of the activity among seasons, as well as the vessels' characteristics (definition of all activity profile variables: "Def_flotille.qmd" file). The results obtained were compared with existing IFREMER classifications ("Fleets_comparisons.qmd" file). The same operations were performed to classify vessels's trip into different fishing tactics, with again a definition of fishing activities at this scale (Def_tactics.qmd) and a classification treatment of trips (Classification_trip_tactics.qmd).


## Roadmap

This project is part of a larger framework that seeks to build an analytical pipeline from the definition of a fleet to its impact on the risk of incidental catch of non-target species (see Accidental_bycatch_explo.qmd file for exploratory analyses on it, including a random forest approach to estimate bycatch risk). The next steps will aim to use the modeling tools developed by Authier et al. 2022 ([https://www.frontiersin.org](https://www.frontiersin.org/articles/10.3389/fmars.2021.719956/full)) to best estimate the risk of incidental catches, taking the case study of the common dolphin in the Gulf of Biscay.


## Authors and acknowledgment

This project is developed in the context of the DELMOGES project ([https://delmoges.fr](https://delmoges.recherche.univ-lr.fr/)), and more precisely for the working group aiming at better describing the bycatch risk in the Bay of Biscay for common dolphin ([https://delmoges.fr/wp3-interactions-dolphins-fisheries](https://delmoges.recherche.univ-lr.fr/presentation-du-projet/wp3-interactions-dauphins-pecheries/)). The framework developed here is realized in the context of a post-doctoral contract (Mathieu Brevet) supervised by Laurent Dubroca (IFREMER, Laboratoire Ressources Halieutiques de Port-en-Bessin) and Matthieu Authier (Observatoire PELAGIS).


## Project status

This project is currently under development.

