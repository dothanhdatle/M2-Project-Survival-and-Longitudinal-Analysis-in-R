# M2-Project-Survival-and-Longitudinal-Analysis-in-R
**Survival analysis on the mortality of COVID-19**

During the latter of 2019, the world was hit by a sudden and widespread outbreak of COVID-19, a disease that originated in Wuhan, China. It quickly spread across the globe, posing one of the biggest challenges humanity has faced in recent times. COVID-19 is highly contagious and can spread through the air from person to person, making it difficult to prevent contact between infected and non-infected individuals. Due to the challenges posed by this disease, the death rate among infected people has been increasing steadily. In our project, We used the Cox proportional hazards model to analyze the relationship between patient variables, such as age, symptoms, and chronic diseases, and time to death. The dataset we received was not initially structured for survival analysis. Therefore, our primary task was to clean the data, which is a critical step in ensuring precise analysis. We extracted relevant features and eliminated irrelevant ones from the original dataset for our study. We then used graphical and numerical summaries to explore the features of the dataset and check the survival function in the subgroups defined by each categorical variable. Next, we applied two types of the Cox model to our dataset: one with a linear relationship and the other with a non-linear relationship. In addition, we also intended to use the Random Forest machine learning model, which is a tree-based model, and compare its performance with the Cox model to select the better one for our project.
