# Analysis of the association between bacteriophages and related strains Pseudomonas Aeruginosa bacteria

Bacterial infections has always been considered one of the most crucial challenge in the clinical field until the discover and use of penicillin. However. the indiscriminate use of antibiotics has led to the emergence of multi-resistant bacterial strains. This leads us to the use of alternative therapies to antibiotics, such as phage therapy, which uses viruses to deal with bacteria. For the correct use of this therapy, it is completely necessary to know which phages infect each bacterium and what their features are. In addition, it is also useful to know what are the defense systems used for bacteria to deal with these viruses. By analyzing  thousands of genomes from Pseudomonas aeruginosa bacteria, we have identified all phages integrated in their genomes and we have related them with different features of the bacterial strains, such as the geographical location, the isolation source or CRISPR-Cas systems. These results show a co-ocurrence of some phages and CRISPR-Cas systems, while the rest of strain features do not correlate. This allows the elaboration of a catalog of phages positively and negatively associated  with the different types of CRISPR-Cas systems, which is potentially useful for the application of phage therapy. f

Phages infect bacteria to replicate themselves using bacterial machinery, This virulent process ends in the lysis of bacterial membrane and the liberation of the phage copies. In some cases, phages can integrate into the bacterial genome as temperate phages or prophages, that are those sequences which we predicted from genomes.
To deal with these exogenous agents, bacteria have developed different defense systems, such as CRISPR-Cas systems, which can recognize phages in a specific way and remove them. 

![imagen](https://github.com/amorrod/JABI2023/assets/137997372/e0d4514d-e190-41d5-89d6-8247adedf8b1)

Figure 1.- Infective and defensive process of bacteriophages. 
The red pathway shows the viral infection of a bacterium by a bacteriophage, which inserts its DN inside the cell and uses all the celular machinery to replicate itself. Once it has replicate, these copies are released abroad through the lysate of the bacterium. The green pathway shows how bacteria defend themselves and confront phage infection using the CRISPR-Cas defense system.


Phage sequences were searched for and classified by taxonomy in all genomes of Pseudomonas aeruginosa. In order to eliminate redundancy between sequences, phages were clustered by similarity. 

![imagen](https://github.com/amorrod/JABI2023/assets/137997372/c2040ab7-a61e-4bd9-95a6-847b7054f429)

Figure 2.- Protocol of phage search and clustering.
The first step was the prediction and identification of all phages from the avalaible genomes of Pseudomonas aeruginosa using the bioinformatic software Phigaro. The second step was the clustering of the phage sequences to remove the redundancy between sequences using the clustering tool MeShClust.


Also, CRISPR-Cas systems were searched for in Pseudomonas 
aeruginosa genomes (CRISPRCasTyper). Spacers of these defense systems were identified (CRISPRCasFinder). 

![imagen](https://github.com/amorrod/JABI2023/assets/137997372/41d4f58f-d71e-4982-ade6-3a1cfaca4794)

Figure 3.- CRISPR-Cas types in Pseudomonas aeruginosa.
Percentage of strains that possess each type of CRISPR-Cas system (and not possessing CRISPR-Cas system).

We were able to determine the wide diversity of phages in Pseudomonas aeruginosa thanks to a deep clustering process and the use of multiple strain metadata. We considered as a complete phage any sequence larger than 8 kb. 


![imagen](https://github.com/amorrod/JABI2023/assets/137997372/699ff54e-3944-4e1a-984d-aaf8e143fd71)

Figure 4.- Identification of phages.
(A) Frequency of the sizes of clusters with at least 10 clustered phages. (B) Distribution of predicted phage lengths, where the green line represents the mean length, the blue line represents median length, and the red line refers to the 10000 bp threshold.


Some of these features, such as geographic location or isolation source, did not correlate with phages.
According to the defense systems, most of phages are in strains without CRISPR-Cas systems, which is to be expected since bacteria use these systems to face them. However, some phages are significantly related to some CRISPR-Cas systems, such as I-F or I-E types.

![imagen](https://github.com/amorrod/JABI2023/assets/137997372/d327d68e-a598-4988-bd14-3c2c57a6b533)

B ![imagen](https://github.com/amorrod/JABI2023/assets/137997372/49330d36-ed90-4c66-8638-b9246d56430b)

Figure 5.- Distribution of CRISPR-Cas types across strains containing the most abundant phages.
(A) The non-blank color indicates the presence of phages (X axis) in the corresponding strain genome (Y axis). Only the 25 most frequent phages in P. aeruginosa strains are shown. They are sorted by presence and colored by taxonomy. The left side of the plot shows the different types of CRISPR-Cas systems of the strains, in which the CRISPR types that appear in less than 10 strains are classified as ‘other’. In addition to CRISPR types, the MLST group of each strain is shown in all cases. (B) Relative frequency of CRISPR-Cas system types (Y axis) possessed by the strains containing each phage (X axis). Only the 25 most frequent phages are shown, sorted by presence. The bars are filled with different colors based on CRISPR types.

We searched for spacers against phages related to strains without CRISPR-Cas systems to know what type of CRISPR-Cas system faces these phages. Phages which are significantly increased in strains no CRISPR were significantly decreased in strains with CRISPR-Cas systems, particularly with type I-F systems. This type of CRISPR-Cas system has spacers against these phages

![imagen](https://github.com/amorrod/JABI2023/assets/137997372/e8b6822d-9de1-4ba7-b06b-d792fefbb5ea)

B      
 ![imagen](https://github.com/amorrod/JABI2023/assets/137997372/e59c1c75-1432-4936-a52d-8e5731fdfa69)

Figure 6.- Differences in the number of phages in strains with and without CRISPR-Cas systems.
It is shown the bar plots about significant differences in the number of phages in type I-F CRISPR-Cas system strains and no CRISPR strains. It also shows the number of spacers against decreased or increased phages and the p-value about the difference of each phage. The gray bars represent the expected value calculated from the number of genomes containing the phages and the total number of genomes with or without the CRISPR array. The observed value bars are colored in red when the observed number of phages is less than expected or in green when the observed values of phages is greater than expected.
(A) The bar plot shows phages that are significantly reduced in strains with type I-F CRISPR-Cas systems. (B) The bar plot shows phages that are significantly increased in strains without CRISPR-Cas systems.



Knowing which bacteriophages can infect a certain bacterial species, as well as how bacteria defend themselves against these viruses, is essential for a better understanding of bacterial biology and for developing alternative approaches in the battle against bacteria, such as phage therapy.


Rubio, A., Sprang, M., Garzón, A., Moreno-Rodriguez, A., Pachón-Ibáñez, M. E., Pachón, J., Andrade-Navarro, M. A., & Pérez-Pulido, A. J. (2023). Analysis of bacterial pangenomes reduces CRISPR dark matter and reveals strong association between membranome and CRISPR-Cas systems. Science Advances, 9(12). https://doi.org/10.1126/SCIADV.ADD8911


