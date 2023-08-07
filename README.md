# Project 03. "Fake review finder"

## Table of Contents 
[1. Project description](README.md#project-description)  
[2. Problem Statement](README.md#problem-statement)  
[3. Brief Data Overview](README.md#brief-data-overview)  
[4. Project Stages](README.md#project-stages)  
[5. Results](README.md#results)    
[6. Conclusions](README.md#conclusions) 


### Project description    
This project is dedicated to transforming hotel review data for the purpose of training a model to predict reviews from input data and detect fake ones.

:arrow_up:[to top](README.md#table-of-contents)


### Problem Statement    
The hospitality industry occasionally resorts to posting fabricated reviews to artificially inflate their ratings. Leveraging data obtained from Booking.com, this project aims to address the challenge of designing pertinent features and training a predictive model for assessing hotel reviews, with a primary focus on identifying deceptive feedback.

:arrow_up:[to top](README.md#table-of-contents)


### Brief Data Overview
The input dataset, named "hotels.csv," features the following structured information:

* hotel_address: The address of the hotel.
* review_date: The date when the reviewer posted the corresponding review.
* average_score: The hotel's average score, calculated based on the latest comment within the last year.
* hotel_name: The name of the hotel.
* reviewer_nationality: The nationality of the reviewer.
* negative_review: A negative review provided by the reviewer for the hotel.
* review_total_negative_word_counts: The total number of words in the negative review.
* positive_review: A positive review provided by the reviewer for the hotel.
* review_total_positive_word_counts: The total number of words in the positive review.
* reviewer_score: The score assigned by the reviewer to the hotel based on their experience.
* total_number_of_reviews_reviewer_has_given: The total number of reviews the reviewer has given in the past.
* total_number_of_reviews: The overall count of valid reviews about the hotel.
* tags: Tags assigned by the reviewer to the hotel.
* days_since_review: The number of days between the review date and the cleanup date.
* additional_number_of_scoring: Some guests have solely provided a service rating without leaving a review. This number indicates how many valid ratings are present without a review.
* lat: The geographical latitude of the hotel.
* lng: The geographical longitude of the hotel.

This dataset serves as the foundation for the project's objectives, which involve the development of a model capable of predicting hotel reviews and distinguishing genuine feedback from fabricated ones. The project aims to enhance the credibility of hotel rating systems, ensuring a more reliable and informative experience for consumers in the hospitality sector.

![hotels.csv](https://drive.google.com/file/d/1eo4npcuCV57MlVQ6YT4ElJ-y-ZD0Rz2J)

:arrow_up:[to top](README.md#table-of-contents)


### Project Stages  
1. Preliminary data analysis.   
    Conduct an initial analysis of the data to understand its structure, quality, and possible patterns. This includes studying basic statistics and identifying missing values.
2. Feature Engineering:   
    Design and create new features that capture relevant information from the dataset. This could involve extracting sentiment scores from reviews, generating aggregate statistics, or encoding categorical variables.
3. Feature Selection Based on Importance:   
    Evaluate the importance of features in relation to the predictive task. Utilize techniques like feature importance scores or correlation analysis to determine which features contribute significantly to the model's performance.
4. Removal of Insignificant and Highly Correlated Features:   
    Eliminate features that exhibit low importance or are strongly correlated with each other. This step aims to enhance model interpretability and prevent issues like multicollinearity.
5. Model Training:  
    Training a Predictive Model Using the RandomForest Machine Learning Algorithm
6. MAPE Metric Evaluation:  
    Validate the model's performance using the Mean Absolute Percentage Error (MAPE) metric. Calculate the MAPE for the predictions made by the model and the actual values. MAPE provides insights into the accuracy of the model's predictions, particularly when dealing with percentage-based errors.


:arrow_up:[to top](README.md#table-of-contents)


### Results:  
As a result of the project, a predictive model was successfully constructed with a prediction accuracy of 88.32% (11.68% error rate) in estimating hotel reviews. This achievement demonstrates the model's capability to effectively forecast review scores and, consequently, its potential to distinguish genuine reviews from fabricated ones. The project's outcomes signify a significant advancement in enhancing the accuracy and reliability of hotel review systems, thus contributing to the improvement of user experiences within the hospitality industry.

:arrow_up:[to top](README.md#table-of-contents)


### Conclusions:  
In conclusion, it can be stated that there is further potential to enhance the model's accuracy. The project has been presented in its current state due to limitations in computational resources, preventing extensive iterations and more rigorous feature selection. However, the existing model demonstrates a commendable capability to predict review scores with a satisfactory accuracy level.

The decision to revisit and refine the project in the future reflects a proactive approach towards improving the model's performance. By conducting thorough feature selection and additional iterations, it is anticipated that the model's predictive prowess can be further elevated.

Overall, the project's outcomes highlight the model's proficient ability to estimate review scores with a significant degree of accuracy. This accomplishment holds promise for bolstering the effectiveness of review systems in the hospitality domain, ultimately contributing to elevated user satisfaction and informed decision-making processes.

:arrow_up:[to top](README.md#table-of-contents)


If you find the information about this project interesting or useful, I would greatly appreciate it if you could consider giving the repository and profile a ⭐️⭐️⭐️ rating. Your support would mean a lot!