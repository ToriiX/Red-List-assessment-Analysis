# IUSN Red-List Assessment Analysis



### "Established in 1964, the International Union for Conservation of Nature’s Red List of Threatened Species has evolved to become the world’s most comprehensive information source on the global extinction risk status of animal, fungus and plant species." (IUCN)

#### Data was downloaded from the IUCN Red List in January 2024. https://www.iucnredlist.org/en
#### Uploaded and Analysed with Python in Jupyter Notebook

## Objective:
#### In this project, I wanted to investigate the overall comprehensiveness of the Red List, and if there are considerations that need to be taken if using the list as a guideline for wildlife conservation actions and measures. 

## Conclusion:
#### The IUCN Red List contains a biased representation of wildlife. Most of the included classes have few assessed species, while a few classes are vastly overrepresented compared to the rest. A large amount of the species included in the list (28%) have the status threatened. The high number of threatened species could be influenced by the likelihood of scientists being more skewed towards assessing species assumed vulnerable/threatened for the Red List than those assumed to be of lesser concern. It should be noted that the classes of organisms which are the most threatened do not necessarily mirror the most studied/ those receiving the most attention. This should be taken into consideration in conservation actions and measures.

## Research questions:
1. Which classes have the greatest number of assessed species?
2. What is the assessment status distribution of the classes with the most assessed species, and how many per cent of species are threatened in total?
3. Which classes have the least number of assessed species? 
4. What is the distribution of  the total number of assessed species among the classes?
5. Which classes have the greatest number of extinct species?
6. Which classes have the greatest number of threatened species?
7. Is there a correlation between the number of threatened species in a class and the amount of assessed species in a class?
8. Which classes have the greatest percentage of threatened species? (Only including classes with more than 100 assessed species)
9. Which 10 classes have the greatest percentage of extinct species? (Only including classes with more than 100 assessed species)
10. Is there a correlation between the number of threatened species and the percentage of threatened species in the classes?


    

![image](https://github.com/ToriiX/Red-List-assessment-Analysis/assets/156717220/cbdd7872-f0ce-4667-b4e1-b59450a83efe)


Figure: A) MAGNOLIOPSIDA (Magnolia Plants), B) ACTINOPTERYGII	(Ray-Finned fish), C) BIVALVIA (class of molluscs), D) CYCADOPSIDA (Cyads), E) ARACHNIDA (Joint-Legged arthropods), F) AGARICOMYCETES (Class of Basidiomycota fungi). Photo source: Creative Commons.
 


## Results:
1. Magnolia Plants and Ray-Finned Fish were the classes with the most assessed species. 
2. The majority of the species had the status Conservation Dependent/Least Risk/Least Concern, followed by Threatened and Data Deficient. In total 28% of all species were threatened.
3. There were many classes with few assessed species. In total, there were 35 classes out of 68 classes with less than 20 assessed species. 
4. The number of assessed species per class varied greatly from 1 to 51471 species.  Most of the 68 classes included in the Red List had few assessed species, with 75% of the classes having less than 454 assessed species, and 50% of the classes less than 17. 
5. Snails and Slugs, followed by Birds, and Magnolia Plants had the greatest number of extinct species.
6. Magnolia Plants had by far the greatest number of threatened species.
7. There was a strong correlation between the number of assessed species in a class and the number of threatened species in the same class. 
8. The class of plants Cyads had the greatest percentage of threatened species. Plants dominated the 10 classes with the greatest percentage of threatened species. Of animals, Joint-legged Arthropods had the greatest percentage of threatened species, while it in the Fungi Kingdom were Agaricomycetes. 
9. BivalVia, a class of freshwater and marine molluscs had the greatest percentage of extinct species, closely followed by Snails and Slugs.  Classes of animals dominated the 10 classes with the greatest percentage of threatened species.  Of plants, the classes Bryopsida (Mosses)	and Cyads had the greatest percentage of threatened species. 
10. No correlation was found between the number of threatened species in a class and the percentage of threatened species in a class. 

See code and figures **https://github.com/ToriiX/Red-List-assessment-Analysis/blob/main/The_Red_List_Analysis.ipynb**
