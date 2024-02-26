# GT CSE 6250 Spring Project
**Team A1**
* Brian Popp, [bpopp7@gatech.edu](mailto:bpopp7@gatech.edu)
* Danielle Velott, [dvellot3@gatech.edu](mailto:dvellot3@gatech.edu)

### Summary
Our team will attempt to validate the results of [this paper](https://dl.acm.org/doi/10.1145/3308558.3313698)
and show that a CNN deep learning model can better categorize social media posts 
according to risk for suicide than traditional ML models.

### Instructions

1. Create python environment and install required modules (ie. pip install -r requirements.txt). Note that python 3.11 was used for this exercise.
2. Download [conceptnet](https://conceptnet.s3.amazonaws.com/downloads/2019/numberbatch/numberbatch-en-19.08.txt.gz) word vector and extract to data folder as 'numberbatch-en.txt'
3. run 'python 5-Label-Classification.py' from the models directory.

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