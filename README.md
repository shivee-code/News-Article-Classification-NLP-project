# News-Article-Classification-NLP-project
A machine learning system that automatically categorizes news articles into topics like sports, politics, and technology. This project demonstrates a complete NLP pipeline from data preprocessing to model deployment.

## Project Overview
This project solves the challenge of automatically categorizing large volumes of news articles. With over 50,000 articles in our dataset, manual categorization is impractical. Our solution:

- Achieves 87.2% classification accuracy

- Processes articles in milliseconds

- Understands contextual meaning in news content

- Supports 10+ categories including Politics, Sports, and Technology

### Business Value: 
News organizations can use this system to automate content management, improve recommendation systems, and analyze content trends.

## Features
- **Text Preprocessing Pipeline**: Advanced NLP cleaning and normalization

- **Feature Engineering**: TF-IDF with optimized feature selection

- **Model Comparison**: Logistic Regression vs SVM vs Naive Bayes

- **Hyperparameter Tuning**: Optimized model performance

- **Web Demo**: Interactive classification interface

- **REST API**: For integration with other applications


## Methodology
### Data Pipeline
|          |    |               |    |                    |    |                 |    |             |    |            |
|----------|----|---------------|----|--------------------|----|-----------------|----|-------------|----|------------|
|Raw Text  |➡️  |Preprocessing  |➡️|Feature Extraction  |➡️|Model Training   |➡️|Evaluation   |➡️|Deployment  |

### Technical Approach
**1. Data Collection & Cleaning**
- 50,000 news articles from multiple sources
- Handling missing values and text normalization
- Advanced text preprocessing (lemmatization, stopword removal)

**2. Feature Engineering**
- TF-IDF vectorization with 8,000 features
- N-gram analysis (unigrams and bigrams)
- Dimensionality optimization

**3. Model Development**
- Logistic Regression (best performer)
- Support Vector Machines
- Naive Bayes classifier
- Hyperparameter tuning with RandomizedSearchCV

**4. Evaluation**
- Stratified 5-fold cross-validation
- Precision, Recall, F1-score metrics
- Confusion matrix analysis
- Feature importance visualization

## Results
### Performance Comparison
|**Model**	           |**Accuracy** 	|**Precision** 	|**Recall** 	|**F1-Score**  	|**Training Time**|
|----------------------|--------------|---------------|-------------|---------------|-----------------|
|Logistic Regression	 |    87.2%	    |    87.4%	    |      87.2%	|       87.2%	  |        45 sec   |
|SVM	                 |    86.5%	    |    86.8%	    |      86.5%	|       86.5%	  |        65 sec   |
|Naive Bayes	         |    84.1%	    |    84.3%	    |      84.1%	|       84.1%	  |        12 sec   |
