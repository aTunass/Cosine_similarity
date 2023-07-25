# Cosine_similarity
## Introduces
Use cosine_similarity or Euclidean distance to calculate the correlation between images and text fragments, then query them and return results with high to low correlation.
## Descriptions
- Extract features and save those features as vectors into vector.pkl file. Also save the path of the images with path.pkl
- Extract feature vectors from required image or text then compare them by cosine_similarity or Euclidean distance with all previously saved vectors
## Dataset
[CBIR_dataset]([https://www.youtube.com/watch?v=MvrC0cSQjAA](https://www.kaggle.com/datasets/theaayushbajaj/cbir-dataset)https://www.kaggle.com/datasets/theaayushbajaj/cbir-dataset)
## Dijkstra
- Dijkstra's pathfinding algorithm uses a priority queue to traverse the vertices in the graph in order of path length from the starting vertex to that vertex. Initially, the path length from the starting vertex to itself is assigned zero, and the path length from the starting vertex to the remaining vertices is set to infinity.
- When traversing the vertex u, the algorithm updates the path length from the starting vertex to the vertices adjacent to u, if the new path length is shorter than the old path length, the path length is updated again. Then, vertex u is marked as considered and removed from the priority queue. This process is repeated until all vertices in the graph are considered.
![Alt Text](app/src/main/res/drawable-v24/anh.png)


