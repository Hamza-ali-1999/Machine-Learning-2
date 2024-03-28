# News Modeling

Topic modeling involves **extracting features from document terms** and using
mathematical structures and frameworks like matrix factorization and SVD to generate **clusters or groups of terms** that are distinguishable from each other and these clusters of words form topics or concepts

Topic modeling is a method for **unsupervised classification** of documents, similar to clustering on numeric data

These concepts can be used to interpret the main **themes** of a corpus and also make **semantic connections among words that co-occur together** frequently in various documents

Topic modeling can help in the following areas:
- discovering the **hidden themes** in the collection
- **classifying** the documents into the discovered themes
- using the classification to **organize/summarize/search** the documents

Frameworks and algorithms to build topic models:
- Latent semantic indexing
- Latent Dirichlet allocation
- Non-negative matrix factorization

## Latent Dirichlet Allocation (LDA)
The latent Dirichlet allocation (LDA) technique is a **generative probabilistic model** where each **document is assumed to have a combination of topics** similar to a probabilistic latent semantic indexing model

In simple words, the idea behind LDA is that of two folds:
- each **document** can be described by a **distribution of topics**
- each **topic** can be described by a **distribution of words**