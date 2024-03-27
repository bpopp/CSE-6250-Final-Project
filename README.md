# GT CSE 6250 Spring Project
**Team A1**
* Brian Popp, [bpopp7@gatech.edu](mailto:bpopp7@gatech.edu)
* Danielle Velott, [dvellot3@gatech.edu](mailto:dvellot3@gatech.edu)

Our team will attempt to validate the results of [this paper](https://dl.acm.org/doi/10.1145/3308558.3313698)
and show that a CNN deep learning model can better categorize social media posts 
according to risk for suicide comparted to traditional ML models.

### Google Collab
The google collab show a partial implementation of our solution using a limited dataset
[Google Collab](https://colab.research.google.com/drive/1fVu84WMKqF3Fa7VqJ3zFT6rt5D_TMR9e?usp=sharing)

### Full Source Code Instructions
The full dataset includes source code for building dataset, running and optimizing the models.

(Note that python 3.11 was used to build this project.)

1. Create python environment and install required modules (ie. pip install -r requirements.txt). 
2. Open and run all cells in the file [CSE-6250-Team-A1-Full Source Code.ipynb](https://github.com/bpopp/CSE-6250-Final-Project/blob/main/CSE-6250-Team-A1-Full%20Source%20Code.ipynb)

### Resources

**Paper:**
[Knowledge-Aware Assessment of Severity of Suicide Risk for Early Intervention](https://dl.acm.org/doi/10.1145/3308558.3313698)

**Authors:**
Manas Gaur, Amanuel Alambo, Joy Sain, Ugur Kursuncu, Krishnaprasad Thirunarayan, Ramakanth Kavuluru, Amit Sheth, Randy Welton, Jyotishman Pathak

**Source Code:**
[Github](https://github.com/jpsain/Suicide-Severity)

**Dataset:**
[Github](https://github.com/manasgaur/Knowledge-aware-Assessment-of-Severity-of-Suicide-Risk-for-Early-Intervention)

### Additional Resources

1. [Leveraging Reddit for Suicidal Ideation Detection](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9407719/): excellent article that reviews over 100 studies related to this topic. 
1. [Suicide Risk Assessment Reference Guide](https://www.mentalhealth.va.gov/docs/Suicide_Risk_Assessment_Reference_Guide.pdf): short guide for diagnosing suicidal behavior (manually)
### Methodology 

#### Code Installation and Modernization
1. Minor changes to code organization
1. Updated keras np_utils.to_categorical to utils.to_categorical (api change)
2. General code cleanup for python 3
   * Parentheticized all print statements
   * Added some list comprehension
1. Added a limit to the word2vec function to improve performance while debugging (performance)
2. Minor changes to support gensim 4.0 (api changes)
