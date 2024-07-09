# Medicine Recommendation System 


## Objective
The main goal of this project is to predict diseases based on symptoms inputted by users and provide comprehensive information including disease descriptions, precautions, medications, recommended diets, and workouts.

## Key Components
### Machine Learning Model
- Models Used: SVC, Random Forest Classifier, Decision Tree Classifier, Gradient Boosting Classifier, Multinomial NB, K-Neighbors Classifier.
- Training and Evaluation: Models trained on a dataset, evaluated using techniques like train_test_split and accuracy_score.
- Final Model: Selected SVC (SVC(kernel='linear')) and saved as svc.pkl.
### Web Application (Flask)
- Functionality: Developed using Flask to integrate the machine learning model with a user-friendly interface.
- Pages and Routes: Implemented routes for home, about, developer, and symptoms pages.
- User Interaction: Allows users to input symptoms, predicts diseases, and displays detailed information.
### Data Integration
- Datasets Used: Integrated datasets containing symptoms severity, disease descriptions, diets, medications, precautions, and workouts. - Dataset link: Google Drive
- Helper Functions: Developed functions to fetch detailed information about predicted diseases.
### Benefits and Applications
- Healthcare Accessibility: Provides quick access to disease information based on symptoms.
- Educational Tool: Explains diseases and health recommendations.
- Scalability: Can be expanded to include more diseases and features.
### Future Enhancements
- Real-time Updates: Incorporate real-time data updates and medical database integration.
- User Profiles: Implement user profiles for personalized recommendations.
- Interactive Features: Add features like symptom severity sliders and multi-lingual support.
### Links
- GitHub Code: 
- Dataset link: https://drive.google.com/drive/folders/1KvjW3k79J0q77o_lQsxd6WluTu84mLmx?usp=sharing


# <----------------------------------------------------------------------------------------------------------------------------------->
#                                                                                                    $ Project By : K.Trimal Rao 
# <----------------------------------------------------------------------------------------------------------------------------------->