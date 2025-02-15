**Applied Data Science Capstone**

This Capstone course is the final step in the IBM Data Science Professional Certificate program. It's designed to pull together everything you've learned into one comprehensive project, showcasing your newfound skills and knowledge.

**Project Background**

SpaceX is the most successful company of the commercial space age, making space travel affordable. The company advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. Based on public information and machine learning models, we are going to predict if SpaceX will reuse the first stage.

**Questions to be answered**

- How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
- Does the rate of successful landings increase over the years?
- What is the best algorithm that can be used for binary classification in this case?


**Methodology**

1. Data collection methodology
    - Using SpaceX Rest API
    - Using Web Scrapping from Wikipedia
2. Performed data wrangling
    - Filtering the data
    - Dealing with missing values
    - Using One Hot Encoding to prepare the data to a binary classification
3. Performed exploratory data analysis (EDA) using visualization and SQL
4. Performed interactive visual analytics using Folium and Plotly Dash
    - Build a dashboard to analyze launch records interactively with Plotly Dash as well as build an interactive map to analyze the launch site proximity with Folium python Library.
5. Performed predictive analysis using classification models(Building, hyperparameter tuning and evaluation of the models to ensure best model is used)
    - GridSearchCV for finding best parameters
    - used KNN, Decision Tree, SVM, Logistic Regression classification
