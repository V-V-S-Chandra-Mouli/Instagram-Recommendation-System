# Instagram-Recommendation-System
  This project focuses on the design and implementation of a recommendation system for social media platforms, specifically targeting Instagram. The system is built using a deep learning-based approach, leveraging a two-tower neural network model. The objective is to recommend relevant Instagram profiles or posts to users by learning relationships between user characteristics and content features. The process begins with data collection using the Instagram API via RapidAPI, where user attributes such as verification status and follower counts, along with content metrics like likes and comments, are extracted. After data acquisition, preprocessing techniques are applied to normalize and structure the dataset for optimal model performance.
  The recommendation engine is based on a two-tower architecture where user features and content features are processed through separate neural networks. These networks learn dense representations (embeddings) for both users and posts, which are then compared using a dot product similarity function to assess relevance. The system is designed to deliver personalized recommendations by matching user profiles to the most appropriate posts or accounts. This study demonstrates how deep learning techniques can be effectively applied to solve recommendation problems in social media environments and lays the groundwork for further enhancements through advanced models and additional data enrichment.
