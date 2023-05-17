# Evaluation and Modification of Local Citation Recommendation Systems

## A Comparative Study of Available Embedding and Similarity Search Techniques
>
> ECE-GY 7123: Deep Learning (Spring 2023) Final-Project
>  

### Abstract

This study explores the enhancement of the two-stage Local Citation Recommendation System, initially studied in work **Local Citation Recommendation with Hierarchical-Attention Text Encoder and SciBERT-based Re-ranking.** We have tried to create an alternative system using OpenAI embeddings and OpenAI and Cohere for re-ranking. We conduct an in-depth comparative analysis of these different models, focusing on their impact on the effectiveness of the citation suggestion pipeline. Despite resource constraints limiting us to 100 re-ranked candidates, our findings provide significant insights into the potential advantages and drawbacks of various embedding and similarity search methods. Our new method managed to achieve approximately 5% better accuracy than the one presented in the paper.

### Python notebook contents

- Citation_Recommendation_OpenAI_LLMChainExtractor: In this implementation, we used the LLMChainExtractor in the LangChain library to develop a re-ranking method. This method enables us to use the GPT-3.5-turbo model for re-ranking.
- Citation_Recommendation_OpenAI_CohereReRank: This implementation employed the re-ranking solution provided by Cohere AI. Cohere AI is a platform that allows developers to leverage natural language understanding capabilities in their applications.
- Tutorial_Local_Citation_Recommendation: Original code from paper.

### Acknowledgements

Based on the GitHub [Code](https://github.com/nianlonggu/Local-Citation-Recommendation) for ECIR 2022 paper [Local Citation Recommendation with Hierarchical-Attention Text Encoder and SciBERT-based Re-ranking](https://link.springer.com/chapter/10.1007/978-3-030-99736-6_19)
