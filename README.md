## The goal of this research is to create a reliable and accurate system for classifying YouTube video comments. This technology will automatically group user comments into many categories in order to give video producers, viewers, and moderators useful information. By arranging and comprehending the thoughts, intentions, and different types of interactions stated in the comments section, the main objective is to improve the user experience.

*********************************************************************************************************************
### PROBLEM STATEMENT :

* The problem that needs to be solved in this study is how to efficiently classify YouTube comments based on both sentiment and sentence patterns. Although YouTube comments provide vital insights for video producers, it is challenging to glean useful information due to their vast volume, diversity, and linguistic variances. 

* The goal is to create a classification model that can correctly classify various remark kinds while taking into account feelings (positive, negative), sentence types (interrogative, imperative, etc.), and sentiments (positive, negative). By recognizing pertinent remarks and enhancing the entire viewing experience, the objective is to improve content creators' capacity to interact with their audience. 

* In order to give video creators information that help them make wise content selections and promote better interactions with their audience, a robust solution that can manage the nuances of YouTube comments, such as mixed sentence patterns and moods, is needed.
*********************************************************************************************************************
### CONTEXT OF THE PROBLEM:

* The objective of the study is to categorize comments based on sentiment and phrase style for the purpose of managing YouTube comment feedback. The tools "pandas" for data import, "re" for regex-based preprocessing, and "nltk" for stopword removal are used with Python and Jupyter Notebooks. 

* Spelling correction is handled by the "autocorrect" library. Training includes 80% comments, 20% testing, and Google Colab projects. Cross-validation scores range from 0.76 to 0.85 and F1 scores range from 0.81 to 0.87 when evaluating the performance of a model. 

* The Random Forest classifier struggles with mixed sentence kinds and sentiments in comments, which causes classification errors. It performs best with clear categorizations.

* High-dimensional data causes the Decision Tree Classifier to function inadequately. Dealing with different comment formats presents difficulties that affect categorization accuracy, particularly when mixed-sentiment and mixed-sentence situations appear on YouTube videos.


*********************************************************************************************************************
# Youtube Comments Categorization

This repo is for categorizing comments on a youtube video into different categories.
  - negative (grievances, complaints, ...)
  - positive (appreciation, ..)
  - imperative (requests, suggestions, commands, ...)
  - interrogative (wh, yrs/no)
  - corrective
  - others

## Requirments
  - Jupyter notebook
  - google account (onyl if you use scraping tool)

## Instructions
  - setup virtual env
  - install the required libraries using "requirements.txt" file. (pip install -r requirements.txt)
  - "main.ipynb" is the main file where the new concept is implemented
