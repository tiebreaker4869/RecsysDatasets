# README

This repository contains preprocessed datasets for recommender systems research. Our preprocessing methodology follows established practices in the field:

- **Time-based Filtering**: We remove reviews before specified dates to maintain manageable dataset sizes while preserving temporal patterns.
- **Cold-start User Elimination**: K-core filtering is applied to ensure all users have sufficient interaction data, improving model training stability.