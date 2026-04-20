This is the repository for the final project of INFSCI 2160 data mining

This project uses the news articles for political bias classification dataset from Kaggle
https://www.kaggle.com/datasets/gandpablo/news-articles-for-political-bias-classification

For zero shot classification, I used the below HuggingFace model
https://huggingface.co/bucketresearch/politicalBiasBERT

There are 4 notebooks in this repo, which does require some sequential running in order to generate the relevant CSVs
It should be run in the order of ScatterText -> HuggingFace_Embeddings -> Rest of the 3 notebooks

For the sake of saving the user time on the visualization generation, I've provided visualizations in the repo