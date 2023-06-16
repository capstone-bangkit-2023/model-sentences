# Sentences Model
This sentence similarity model serves to check the similarity between the answers that come from the user and the answers in the question database. In this sentence similarity model, each sentence is put into a transformer model. Each sentence is processed into a representation matrix. Then the processing results are pooled which aims to reduce the spatial dimension of the input representation. Then the two matrices are compared using the cosine similarity function to see the similarity of the two sentences.

# Dataset
In this sentence similarity model, we use a dataset containing essay questions and their answers. The essay questions we take cover several subjects at the high school level, such as Indonesian language, biology, physics, chemistry, and others. In each subject, there are fifteen essay questions at the high school level. We get this dataset by searching for questions from several sources, such as books and the internet.
