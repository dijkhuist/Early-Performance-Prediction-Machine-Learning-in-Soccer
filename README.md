# Early-Performance-Prediction-Machine-Learning-in-Soccer
This repository contains the code and the access to the data of the publication 'Early Prediction of Physical Performance in Elite Soccer Matches - A Machine Learning Approach to Support Substitutions', Entropy, Data Analytics in Sports Sciences: Changing the Game,2021 

There are five folders

- Animations containing:\
  Animations notebooks generating movies based on the match data and example movies:\
  -Animation Match.ipynb => enables a visualisation of a match in a movie (mp4)\
  -Match-Centroid and Eucledian Distance.ipynb => enables a visualisation of the centroid of a team (mp4)\
  -one_min_match.mp4 => a result of Animation Match.ipynb\
  -results38_one_min_centroid_match.mp4 => a result of Match-Centroid and Eucledian Distance.ipynb
\
- Connect to the Data containing:\
  -Introduction to connect to the data => username/password/machine/database and recommended tooling to access the data.\
  
- Data Model Descriptions containing:\
  -Data model and Data model descriptions of the results/metrics of the generated machine learning models:\
   Data Model Machine Learning Metrics.pdf and Data Model Machine Learning Metrics Descriptions.pdf\
  -Data model and Data model descriptions of the soccer match tracking data:\
   Data Model Soccer.pdf and Data Model Soccer Descriptions.pdf\
  -The description of the views containing the realized features for the algorithms:\
   Views Machine Learning Features.pdf and Views Machine Learning Features Descriptions.pdf 
   
- Visualization and Statistics containing:\
  -The notebooks with the description of the data, visualisation of the data and the statistics of the data categorized by the three variables\
  Energy expenditure in power category, Distance in speedcategory and Distance covered. The information was conducted for both entire match players and substitutes.\
  -Visualizations and Statistics Distance covered entite match.ipynb(also containing the description but the name length is limited)\
  -Visualizations and Statistics Distance covered substitutes.ipynb(also containing the description but the name length is limited)\
  -Visualizations and Statistics Distance in speedcategory E-match and sub.ipynb (also containing the description but the name length is limited, E-match = entire match, sub = substitutes)\
  -Visualizations and Statistics of Energy in powercategory E-match and sub.ipynb (also containing the description but the name length is limited, E-match = entire match, sub = substitutes)
  
- Prediction containing:\
  -Notebooks and generated machine learning models for the thresholds 90%/95%/100% of the normal physical performance of a soccer player,\
  categorized in the variables Energy expenditure in power category,Distance in speedcategory and Distance covered,\
  using three different algorithms Bayes, Tree and Random Forest.\
  -Notebooks generating the models (including metrics etc):\
   -Soccer Notebook to predict on Distance.ipynb\-
   -Soccer Notebook to Predict on Distance in speedcategory.ipynb\ 
   -Soccer Notebook to predict on Energy Expenditure in powercategory.ipynb
  
  Machine Learning Models\
  folder: app=>pickeled_models => all generated machine models (sometimes in rar because the limit of github, please extract to use)
  
-
 

 
 


