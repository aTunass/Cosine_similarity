# Cosine_similarity
## Introduces
Use cosine_similarity or Euclidean distance to calculate the correlation between images and text fragments, then query them and return results with high to low correlation.
## Descriptions
### Image_retrieval
- Extract features and save those features as vectors into vector.pkl file. Also save the path of the images with path.pkl
- Extract feature vectors from required image or text then compare them by cosine_similarity or Euclidean distance with all previously saved vectors
### Text_retrieval
- Make a corpus (list document)
- Make a dictionary from corpus (including standardized single words)
- Make a Doc_Term_Matrix form corpus and dictionary (including standardized and vectorized docs)
- Vectorizing query and using cosine similarity between Doc_Term_Matrix and Query
- The results are the docs that have the most correlation with the given query
- ![Alt Text](https://i.imgur.com/cz569iL.png)
## Dataset
- [CBIR_dataset](https://www.kaggle.com/datasets/theaayushbajaj/cbir-dataset)
- [MS MACRO Dataset](https://huggingface.co/datasets/ms_marco)
## Reference
- [Mi_AI](https://www.youtube.com/watch?v=C42lHmnNFe8)
- [AIO]


