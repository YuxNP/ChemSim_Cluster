# ChemSim_Cluster
This is the showcase for chemical similarity studies.

1.Type 2: This type of chemical similarity study is used in analogue studies based on MS2 features.
This method provides an implementation of a similarity-based framework designed to analyze molecular variations from MS2 spectra. The method captures fine-scale structural modifications using optimized similarity calculations and transformation mapping techniques.
- Importance: The data needs to undergo strict preprocessing before the similarity study to remove noise, standardize values, and exclude unnecessary data points.
- This method is most suitable for molecules that contain at least five analogues.
- The peak intensity does not matters in current version.
- The molecules must contain at least one unique MS2 fragment that is distinguishable compared to other residues. This allows the code to recognize the unique part, group the analogues, and determine where the molecular changes occur (e.g., Val-Ile-Leu is not a unique residue, but Val-PKS-Leu/Ile is).

2.Type 1:This type of chemical similarity study is used in chemical ecology studies for chemotaxonomy, sample clustering, and unique feature identification based on MS1 features.
This method only considers MS1 features for clustering and finding the unique biomarker based on the chemical composition as well as feature intensity.
- Importance: The samples must undergo qualitative control to ensure that the concentrations are known.
- Duplicate or triplicate samples are recommended.
- Peak intensities do matters in current version of type 1 ChemSim studies. 


The full codes and example data will be uploaded after the article is published.
The currently shown data has had the sensitive parts removed.
