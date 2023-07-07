# Advertisement detection using machine learning
In recent years, ad blocking has grown more prevalent due to the increase in digital advertisements online. This also includes invisible trackers, that are used to track users across the web and create digital profiles. Existing tools to block ads and trackers are plagued with multiple issues, mainly the fact that they can be easily bypassed and need to be continuously updated for maximum ads, or, in some cases, by paying the blocker developers, or are not feasible for a general solution
## Aim
The aim of this project is to create a machine learning model that can classify URLs as ads or trackers.To this end, we have tried various machine learning algorithms to find the most promising algorithm for this project.
## Results
The most promising model is the SVM model that has been tuned using parameters found using the grid search cross validation. The tuned SVM model had a 71 percent accuracy, which is the highest accuracy among all the models. 
## Future plans
It is possible that, with the help of better algorithms and a dataset with more verbose features, the accuracy could be improved on further, thereby making it viable for use in real-world cases.
Another feature that coulbe be implemented is a browser plugin to detect ads and block them
