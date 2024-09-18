# WaterMediated_Hbond: waterbridges_chains
This code runs a loop between two protein chains and returns the water mediated interactions between the interactive residue and atoms, providing a table with the frequency value informing about the probability of that water bridge ocurring during the simulation time. It classifies the water bridges by type, depending on the atom and residue interacting, and after obtaining the results, the data is filtered taking as significant just those interactions where frequency is higher than 0.2


# WaterMediated_Hbond: waterbridges_*SPECIFIC RESIDUES*
These codes classify the different type of interactions between two given specific residues, and then it classify them by time providing and output graph where the x-axis is the simulation time and the y-axis the number of bridges. 

# Histogram of interactions
It provides a visual representation of the distribution of interaction values in our dataset, over the different replicas (3) for each condition. By plotting interaction values on the x-axis and their frequencies on the y-axis, you can see how these values are spread out. It helps in identifying patterns, such as whether most interactions are weak or strong
