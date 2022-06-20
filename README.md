# Lenovo-Customer-Review-Topic-Modelling

![image](https://user-images.githubusercontent.com/70332585/174608884-e610b21a-43c0-4b0b-aa7b-663f27c220ac.png)

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 
Lenovo has launched their budget smartphone in the Indian market. The client wants to understand the VOC (voice of the customer) on the product. This will be useful to not just evaluate the current product, but to also get some direction for developing the product pipeline. The client is particularly interested in the different aspects that customers care about. Product reviews by customers on a leading e-commerce site should provide a good view.

## 2. Installation <a name="installation"></a>

- Python - [Jupyter Notebook](https://jupyter.org)
- Libraries :
  - pandas
  - numpy
  - re
  - string
  - nltk
      - WordNetLemmatizer
      - pos_tag
      - stopwords
  - gensim
  - pyLDAvis

  
## 3. Data<a name="data"></a> 

Uploaded above by the name : ["K8 Reviews v0.2.csv"](https://github.com/piyushkumar08/Lenovo-Customer-Review-Topic-Modelling/blob/main/K8%20Reviews%20v0.2.csv)


## 4. Implementation <a name="model"></a> 
- Data preprocessing 
     - case normalisation
     - tokenization
     - lemmatizing (after separation of nouns from the bag of words)
- POS tagging
- Getting only the nouns as Topic modelling is the ultimate goal
- Removing stopwords (if there are any)
- Creating the topics using LDA

## 5. Result<a name="results"></a>
The details of the results are shown in the jupyter notebook itself along the source code. Click here to see the result -> [Result](https://github.com/piyushkumar08/Lenovo-Customer-Review-Topic-Modelling/blob/main/Lenovo%20Customer%20Review%20Project.ipynb) 

