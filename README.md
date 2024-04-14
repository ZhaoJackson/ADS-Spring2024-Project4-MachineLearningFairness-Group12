# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2024

+ Team 12
+ Projec title: Machine Learning Fairness
+ Team members
	+ Tianyi Xia
	+ Peng Jiang
	+ Nicolette Auld-Griffith
	+ Jackson Zhao
	+ Danielle Solomon
   
+ 1. Fairness-aware Feature Selection:
    - Focuses on selecting features that reduce discrimination in predictive modeling.
    - Proposes a method to identify and exclude features that contribute to unfair predictions towards certain groups, based on sensitive attributes like gender or race.
    - Emphasizes maintaining the predictive performance of the machine learning model while enhancing fairness.
    - Suggests techniques for evaluating the fairness of a model post-feature selection.

+ 2. Handling Conditional Discrimination:
    - Addresses the issue of conditional discrimination, where bias is not absolute but conditional on certain attributes.
    - Introduces algorithms designed to modify the training data or the learning process to minimize conditional discrimination, ensuring that the machine learning model's decisions are fair across different groups defined by sensitive attributes.
    - Highlights the importance of considering explainable factors that may justify differences in predictions across groups, thereby allowing for fairer decision-making processes.
    - Presents experimental results demonstrating the effectiveness of the proposed methods in reducing conditional discrimination without significantly compromising the accuracy of the model.

+ Methodology Differences:
    - Feature Selection: The first article suggests a pre-processing step focusing on feature selection to enhance fairness, which could be a strategic starting point for your project. This involves analyzing and choosing features that are less likely to introduce bias into the model.
    - Conditional Discrimination: The second article's methodologies are more focused on adjusting the model or data to address conditional biases, making it crucial for developing algorithms that are sensitive to the nuances of discrimination.

+ Local Massaging
    - Objective: Adjust labels within each age category to mitigate bias and balance the probability of recidivism between males and females.

+ Preferential Sampling
    - Objective: Modify the dataset composition by deleting and duplicating instances to create a more balanced dataset that does not reinforce existing biases.
	
**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
