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
2. Download [conceptnet](https://conceptnet.s3.amazonaws.com/downloads/2019/numberbatch/numberbatch-en-19.08.txt.gz) to Data folder

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

### Methodology 

#### Code Reproduction
1. Minor changes to code organization
1. Updated keras np_utils.to_categorical to utils.to_categorical (api change)
1. Parentheticized all print statements (python deprecation)
