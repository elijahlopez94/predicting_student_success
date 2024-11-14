![alt text](path_to_banner_image)
# Predicting Student Success with Machine Learning
Author: Elijah Lopez


## Overview
This analysis reveals key predictors of student outcomes, emphasizing the influence of class time, scholarship status, credit approval trends, and graded units on student outcomes (dropout, continued enrollment, and graduate). Results indicate that students in morning classes experience better outcomes compared to those in evening classes, with the latter group showing a higher dropout risk. Scholarship recipients also have notably higher graduation rates. Additionally, students who experience a significant drop in approved credits from first to second semester are more likely to drop out, while students who maintain or increase their graded units tend to continue or graduate. These findings inform several actionable recommendations, such as targeting at-risk evening students for additional support, emphasizing scholarship access, and monitoring credit approvals to identify and intervene with students at risk of not progressing. By implementing these strategies, institutions can enhance student success rates and reduce dropout risks.


## Business Problem
Student outcomes are crucial to a variety of stakeholders. Successful students gain better employment opportunities, while educational institutions enhance their credibility and reputation. Furthermore, positive student outcomes play a key role in helping institutions secure funding from both government sources and private donors. Key metrics such as dropout rates, continued enrollment, and graduation rates are of utmost importance to these stakeholders. This report examines the leading indicators for each outcome and incorporates a machine learning prediction model to identify students at risk of dropping out. By identifying at-risk students early, academic advisors and student services can proactively intervene and develop tailored strategies to improve their chances of graduating.


## Data
This data was originally published in Advances in Intelligent Systems and Computing and was accessed through [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success). It contains data for roughly 4,400 students, measured across 35 features + outcome ('Dropout', 'Enrolled', 'Graduate'). It included a mixture of demographic data from the student and their parents as well as performance by unit counts for semesters 1 and 2. The data was further categorized by binary, cardinal, ordinal, other categorical, and numeric types.
* ~4,400 students
* Measured on 35 features + outcome
* Mix of:
    * Demographics, including parent backgrounds
    * Student performance in two semesters
* Data further categorize by:
    * Binary features
    * Cardinal features
    * Ordinal features
    * Other categorical
    * Numeric features


## Methods
I first focused on categorical features, performing statistical tests for:
* Rate of Student Outcomes by Class Time (morning and evening)
* Rate of Student Outcomes by Displacement
* Graduation Rates vs Scholarship Status

Next I focused numeric features, performing statistical tests for:
* Student Outcomes vs Units Approved
* Student Outcomes vs Units Graded

Finally, I creeated a machine learning model.
In attempt to tune the model I handled data in this way:
* Binary features -Left as is
* Cardinal features - Utilized target encoding
* Ordinal features - Ranked and reordered label types to be more logical
* Other categorical - Utilized one hot encoding
* Numeric features - Compared standard scaling and min/max scaling

I also attempted model improvements through:
* 


## Results


### Rec 1
![alt text]('images/rec1.png')

* 


### Rec 2
![alt text]('images/rec2.png')

* 


### Rec 3
![alt text]('images/rec3.png')

* 


### Rec 4
![alt text]('images/rec3.png')

* 


## Conclusions
This analysis leads to three recommendations for 

1. 

2. 

3. 


## Next Steps
*  


## For More Information
See the full analysis in the [Jupyter Notebook](path_to_jupyter_notebook_on_GitHub) or review this [presentation](URL_for_slides). Additionally, all visualizations can be viewed on [Tableau](URL_for_tableau).

For additional info, contact the author at:

Elijah Lopez | elijahlopez94@gmail.com

