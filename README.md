# Spotify-Playlist-Reconstruction-Project

---
**Overview**  
This project aims to reconstruct Spotify users' Top-of-the-Year playlists for 2018–2024 following a data breach. Additionally, the project proposes a recommendation algorithm to enhance user experience.

**Objectives**  
1. Reconstruct individual playlists from a mixed dataset.  
2. Develop a recommendation system using contextual and historical data.  

**Tools and Methods**  
- **Data Analysis and Visualization**: Pandas, NumPy, Matplotlib, Seaborn.  
- **Machine Learning Models**: Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees.  
- **Preprocessing and Evaluation**: Feature engineering, hyperparameter tuning, accuracy metrics.  

---

### Workflow and Insights

1. **Data Preprocessing**  
   - Cleaned and transformed the dataset to ensure compatibility with models.  
   - Encoded categorical features and scaled numerical features for uniformity.  
   - Removed irrelevant and duplicate data entries.  

2. **Model Building**  
   - **Logistic Regression**: Applied the OneVsRest strategy for multi-class classification.  
   - **KNN**: Tuned hyperparameters like 'k' and distance metrics to optimize performance.  
   - **Decision Tree**: Enhanced with RandomizedSearchCV and cross-validation.  

3. **Evaluation**  
   - Logistic Regression showed the highest accuracy for playlist reconstruction.  
   - Confusion matrices provided insights into model strengths and areas for improvement.  

4. **Playlist Reconstruction**  
   - Successfully reconstructed user playlists for individual years (2018–2024).  
   - Exported reconstructed playlists as `.csv` files for further use.  

5. **Recommendation Algorithm**  
   - Proposed a hybrid recommendation system combining content-based and collaborative filtering.  
   - Leveraged user preferences, song attributes, and contextual data (mood, seasonality, events).  

---

### Key Insights  
- Logistic Regression outperformed other models in accuracy and prediction reliability.  
- A hybrid recommendation system ensures personalized suggestions by integrating user behavior and song features.  
- The workflow demonstrated the importance of preprocessing and hyperparameter tuning for successful reconstruction and recommendation.

**Conclusion**  
This project successfully reconstructed Spotify playlists and provided a robust recommendation algorithm framework. These methods enhance user experience and provide valuable insights for handling future data-related challenges.
