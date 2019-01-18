-----------------------------------------------------------README.txt-----------------------------------------------------------

                            A Netflix Tour of Data Science - Film suggestion by diffusion on graphs


------------------- Team

Team 17
Edwige Avignon, Kenneth Nguyen, Pierre Fourcade


------------------- Usefull informations

This repository is cut into different notebooks and folder. 

The main notebook, holding the key parts of the code for the application we want to realise is entitled: "A_Netflix_Tour_of_Data_Science_Film_suggestion_by_diffusion_on_graphs".
The other notebooks are used to compute data and exports elements needed for the main notebook.
More informations on the different notebooks are available inside the corresponding notebooks.

Already computed data and the dataset used in this project are in the folder: "Dataset_Exports".

------------------- Preparing the data

The different adjacency matrices used in this project couldn't be pushed into the git.
To be able to run correctly the different notebooks it is required to run the following notebooks till the section "2 - Exporting the graph for Gephi (by using Networkx)":
    1. "Adjacency_Cast"
    2. "Adjacency_First_Role"
    3. "Adjacency_Genres"
    4. "Adjacency_Crew"
The other data should have been pushed correctly.

However, if the folder is empty or not present you will need the following dataset as a starting point: Kaggle dataset - Films and Crew.
Then the notebooks must be ran in the following order: 
    1. "Adjacency_Cast"
    2. "Adjacency_First_Role"
    3. "Adjacency_Genres"
    4. "Adjacency_Crew"
    5. At this point the different graphs must be exported to a csv file. We have used Gephi to export those files.
    6. "Signal_Vote_Average"
    7. "A_Netflix_Tour_of_Data_Science_Film_suggestion_by_diffusion_on_graphs"


------------------- License

The content is released under the terms of the MIT License.

