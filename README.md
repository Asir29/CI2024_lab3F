# CI2024_lab3F
Lab3Flipped for Computational Intelligence Course at Polito

The approach for the Path Problem has been understood from the lectures. The road is in the following lines.
-Firstly, is created an undirected graph so that each node is linked to the closest five cities of the dataset.
-Then, defined initial state and goal, a Greedy Best Fist approach is used. The extra info is given as the direction to prioritize (in this case north-west), and the fitness is proportional to how much the city is along this direction.
- A simple backtrack mechanism for stucks is implemented.

The file "find-path-lab3.ipynb" uses "cities/italy.csv" dataset.

Some suggestions for Pandas dataframe operations were given by ChatGPT. 
