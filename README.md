This data repository belongs to the publication "Tree growth-forms reveal dominant browsers shaping the vegetation" by Churski et al. in Functional Ecology

Authors
Marcin Churski<sup>1</sup>, Dries P.J. Kuijper<sup>1</sup>, Katharina Semmelmayer<sup>1</sup>, William J. Bond<sup>2</sup>, Joris P.G.M. Cromsigt<sup>3</sup><sup>,</sup><sup>4</sup>, Yan Wang<sup>5</sup>  & Tristan Charles-Dominique<sup>6</sup><sup>,</sup><sup>7</sup>

Author for correspondence:
Marcin Churski
email: mchurski@ibs.bialowieza.pl

DOI 10.5281/zenodo.12672556

<sup>1</sup>Mammal Research Institute Polish Academy of Sciences, ul. Stoczek 1, 17-230 Białowieża; <sup>2</sup>University of Cape Town, HW Pearson Building, University Ave N, Rondebosch, Cape Town, 7701; <sup>3</sup>SLU, Department of Wildlife, Fish and Environmental Studies, 901 83 Umeå, Sweden; <sup>4</sup>Centre for African Conservation Ecology, Department of Zoology, Nelson Mandela University, PO Box 77000, Gqeberha, 6031, South Africa; <sup>5</sup>Institute for Atmospheric and Earth System Research/Physics, Faculty of Science, University of Helsinki, Helsinki, Finland; <sup>6</sup>AMAP, University of Montpellier, CIRAD, CNRS, INRAE, IRD, Montpellier, France; <sup>7</sup>CNRS UMR7618; Sorbonne University; Institute of Ecology and Environmental Sciences Paris; 4, place Jussieu 75005 PARIS

#### Summary
* Plants adopt particular growth-forms when they are exposed to extreme environmental conditions. In this study, we describe a unique woody plant growth-form induced by large mammalian herbivores and discuss that this growth-form could have evolved as a strategy for escaping the browser zone in herbivore driven ecosystems. 
* We analysed responses of key architectural and morphological attributes (branching and thorn density, tree dimensions, presence of flowers and fruits) of three Eurasian spiny tree species (Malus sylvestris, Prunus cerasifera, Pyrus pyraster) to different levels of browsing by large herbivores in the temperate Białowieża Forest, Poland. 
* Under high browsing pressure, studied trees displayed two distinct forms of the crown: a bottom sterile part developing into a densely branched structure with high density of thorns (‘cage-form’), and an upper reproductive part that escaped from herbivore control (‘escaped-form’). The size of cage-form influenced the feeding behaviour of red deer (Cervus elaphus) by increasing the time deer spend foraging and increasing the bite rate. The height at which cages started to escape and their diameter matched with foraging reach of red deer.
* Synthesis. We argue that the frequency and cage dimensions of this woody growth-form in the landscape could inform on the type and intensity of recent herbivory. Moreover, its distinctive inducibility suggests that this growth-form did not emerge recently under anthropogenic pressure but could be the legacy of ancient herbivory effects. Observational evidence suggests that this growth-form emerged in several herbivore-driven systems around the globe and may be used to identify the dominant herbivores that control vegetation structure in these ecosystems.

Data

The table 'cage_traits.csv' contains data on morphological traits measured on individual trees and was used to describe the key architectural attributes defining the cage and escape forms (trapped branches vs. escaped branches), test if the cage form is induced by mammalian herbivores or not and if the dimensions of the cage form could inform on which animal induced them.

```
Column headers description:

N_Protocol: Tree ID
Status: if the tree individual grow taller than animal reach (escaped or trapped)
Species: tree species
Branch_N: observed branch ID 
Length: branch length (cm)
N_Thorns: number of thorns
N_Twigs: number of twigs
Longest_thorn: the length of longest thorn on the branch (mm)
N_browsed_Twigs: Number of browsed twigs (1) vs non browsed (0) twigs on a branch
Branch_esc: branch position, "escape" indicates the branch growing on the escaped part of a tree
FlowerOrFruit: flower or fruit number found on the branch
BDI: branch density index. It is calculated by twigs number divided by branch length
Thorn_density:Thorn number divided by branch length
BrowRate: observed number of browsed_Twigs divided by branch length
Bite: 1 indicates the branch was browsed, 0 indicated the branch was not browsed.
browsing_environment: if the tree is exposed to high browsing environment or not. 
```

The table 'foraging_time_barplot.csv' contains camera trap data on total foraging time of all the animal on all the tree species and was used to answer the question how the presence of cage form affect herbivore foraging behaviour. This data set was specifically used to produce the bar plot in Figure 5C.

```
Column headers description:
 
N_Protocol : Tree ID
animal_species : observed animal species
Species: tree species
Foraging_time: observed total foraging time.
```

The table 'foraging_time.csv' contains camera trap data on total foraging time of all the animal on all the tree species and was used to answer the question how the presence of cage form affect herbivore foraging behaviour.

```
Column headers description:

N_Protocol: Tree ID
Total_foraging_time: total record foraging time per tree individual
Total_bite_rate : bite rate per tree individual
Bite_rate : bite rate per tree branch
BDI: branch density index. 
Foraging_time_av: record foraging time per tree branch
Surface: the surface of the crown
```

The table 'escape_height.csv' contains data on individual tree heights in relation to their status (escaped vs trapped). This data set was used to test if the dimensions of the cage form could inform on which animal induced them.

```
Column headers description:

N_Protocol: Tree ID
Status: if the tree individual grow taller than animal reach
Species: Tree species
Height: Tree height
```
