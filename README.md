# 🎬 Hybrid Movie Recommendation System  

A hybrid recommender system that combines **Content-Based Filtering** (using TF-IDF) and **Collaborative Filtering** (using TruncatedSVD) to generate **highly personalized and context-aware movie suggestions**.  

The system also includes an **interactive Google Colab interface** built with `ipywidgets`, allowing users to dynamically explore movie recommendations.  


## ⚙️ Features  

- ✅ **Content-Based Filtering**  
  - Uses **TF-IDF vectorization** on movie genres/metadata.  
  - Computes similarity between movies based on textual features.  

- ✅ **Collaborative Filtering**  
  - Applies **TruncatedSVD** on the user–item rating matrix.  
  - Captures latent factors for personalized suggestions.  

- ✅ **Hybrid Scoring Mechanism**  
  - Combines **genre-text similarity** with **latent factor models**.  
  - Improves ranking accuracy for movie recommendations.  

- ✅ **Interactive Interface**  
  - Built with **ipywidgets** in Colab.  
  - Users can select a movie and instantly receive top-N recommendations.  

---


