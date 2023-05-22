**Topic:** Songs Popularity Prediction with Spotify Data<br>

Purpose: The usage of the Spotify streaming platform has been constantly increasing over the years. Automatic prediction of the song
popularity is necessary for such platforms to promote customer engagement and satisfaction. Although various other factors
influence popularity, such as social, demographic, and commercial influences, it would be interesting to address which audio
features influence the popularity of songs. The research focuses on the 1 million song records collected from the Spotify API and
applies machine learning approaches to predict the song’s popularity using classification techniques. The project focuses
on using ensemble and boosting techniques to classify the songs into popular and unpopular categories.


#### Conclusions:
1. Performed resampling using ADASYN as the other methods didn't show significantly high results and it was faster to compute.
2. Out of 5 different classifiers, CatBoost outperformed all of them with higher F1 score.
3. Hyperparameter tuning using gridsearch cv helped in figuring out the best parameters needed for classifying. 
4. Boosting methods can be helpful to handle in case of imbalanced class problems as it gives an edge of penalizing the model for every misclassification for minority class.
5. Recall is an appropriate metric other than F1 score as we could afford an unpopular song getting predicted as popular but a hit shouldn't be classified as unpopular.
6. This is helpful in cases where the music industry members want to verify how the track will perform.

#### Future Scope:
<p>We can get the lyrics and use techniques of NLP to further enhance the model. It is observed that the songs with an explicit content tend to have high popularity and this would be a good approach to further classify our songs.</p>

The web app should launch at http://localhost:8501/
