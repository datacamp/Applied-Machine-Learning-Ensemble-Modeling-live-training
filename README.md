# **Applied Machine Learning: Ensemble Modeling**<br/>by **Lisa Stuart**

Live training sessions are designed to mimic the flow of how a real data scientist would address a problem or a task. As such, a session needs to have some “narrative” where learners are achieving stated learning objectives in the form of a real-life data science task or project. For example, a data visualization live session could be around analyzing a dataset and creating a report with a specific business objective in mind _(ex: analyzing and visualizing churn)_, a data cleaning live session could be about preparing a dataset for analysis etc ... 

As part of the 'Live training Spec' process, you will need to complete the following tasks:

Edit this README by filling in the information for steps 1 - 4.

## Step 1: Foundations 

This part of the 'Live training Spec' process is designed to help guide you through session design by having you think through several key questions. Please make sure to delete the examples provided here for you.

### A. What problem(s) will students learn how to solve? (minimum of 5 problems)

> _Here's an example from the Python for Spreadsheeets Users live session_
>
> - Key considerations to take in when transitioning from spreadsheets to Python.
> - The Data Scientist mindset and keys to success in transitioning to Python.
> - How to import `.xlsx` and `.csv` files into Python using `pandas`.
> - How to filter a DataFrame using `pandas`.
> - How to create new columns out of your DataFrame for more interesting features.
> - Perform exploratory analysis of a DataFrame in `pandas`.
> - How to clean a DataFrame using `pandas` to make it ready for analysis.
> - Create simple, interesting visualizations using `matplotlib`.

> - Key considerations to take in when transitioning from single layer model to stacking layers.
> - The Data Scientist mindset and keys to success in transitioning from baseline models to stacking models.
> - How to select a baseline Machine Learning algorithm
> - Discuss alternative stacking methods
> - Create simple, two-layer regressor and classifier stacked models
> - How to tune hyperparameters using K-fold cross-validation



### B. What technologies, packages, or functions will students use? Please be exhaustive.

> - pandas
> - matplotlib
> - seaborn
> - scikit-learn
> - mlxtend.StackingClassifier
> - vecstack
> - sklearn.ensemble.StackingClassifier
> - sklearn.ensemble.StackingRegressor

### C. What terms or jargon will you define?

_Whether during your opening and closing talk or your live training, you might have to define some terms and jargon to walk students through a problem you’re solving. Intuitive explanations using analogies are encouraged._

> _Here's an example from the [Python for Spreadsheeets Users live session](https://www.datacamp.com/resources/webinars/live-training-python-for-spreadsheet-users)._
> 
> - Packages: Packages are pieces of software we can import to Python. Similar to how we download, install Excel on MacOs, we import pandas on Python. (You can find it at minute 6:30)

> - What is considered a 'weak' learner?
> - Ensemble: In machine learning, a collection of multiple base models combined to create a single model that has better predictive performance than any of the base models used to produce it.  For example, the Random Forest algorithm is an ensemble method that constructs a collection of Decision Trees to output a single trained Random Forest model.
> - Stacking: In machine learning, a collection of multiple base models that use algorithms that are different from one another and used in layers.  The predictions from the layers are used as input in the final layer to produce a final trained model that has better predictive performance than any of the base models used to product it.  Stacking is an ensemble method.

### D. What mistakes or misconceptions do you expect? 

_To help minimize the amount of Q&As and make your live training re-usable, list out some mistakes and misconceptions you think students might encounter along the way._

> _Here's an example from the [Data Visualization in Python live session](https://www.datacamp.com/resources/webinars/data-visualization-in-python)_
> 
> - Anatomy of a matplotlib figure: When calling a matplotlib plot, a figure, axes and plot is being created behind the background. (You can find it at minute 11)
> - As long as you do understand how plots work behind the scenes, you don't need to memorize syntax to customize your plot. 

> - Ensuring the layers are composed of 'weak' learners.
> - Concept of leakage, not leaking information from between layers to avoid overfitting, not generalizing, etc.
> - As long as you understand how base models work behind the scenes, you don't need to memorize arguments to customize your stacking model.

### E. What datasets will you use? 

Live training sessions are designed to walk students through something closer to a real-life data science workflow. Accordingly, the dataset needs to accommodate that user experience. 
As a rule of thumb, your dataset should always answer yes to the following question: 
> Is the dataset/problem I’m working on, something an industry data scientist/analyst could work on? 

Check our [datasets to avoid](https://instructor-support.datacamp.com/en/articles/2360699-datasets-to-avoid) list. 

> - [Abalone Age](https://archive.ics.uci.edu/ml/datasets/abalone)-Regression
> - [Pima Indians Diabetes](https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.csv)-Binary Classification

## Step 2: Who is this session for?

Terms like "beginner" and "expert" mean different things to different people, so we use personas to help instructors clarify a live training's audience. When designing a specific live training, instructors should explain how it will or won't help these people, and what extra skills or prerequisite knowledge they are assuming their students have above and beyond what's included in the persona.

- [ ] Please select the roles and industries that align with your live training. 
- [ ] Include an explanation describing your reasoning and any other relevant information. 

### What roles would this live training be suitable for?

*Check all that apply.*

- [ ] Data Consumer
- [ ] Leader 
- [X] Data Analyst
- [X] Citizen Data Scientist
- [X] Data Scientist
- [X] Data Engineer
- [ ] Database Administrator
- [ ] Statistician
- [X] Machine Learning Scientist
- [ ] Programmer
- [ ] Other (please describe)

### What industries would this apply to?

*List one or more industries that the content would be appropriate for.*
Industry Agnostic


### What level of expertise should learners have before beginning the live training?

*List three or more examples of skills that you expect learners to have before beginning the live training*

> - Can draw common plot types (scatter, bar, histogram) using matplotlib and interpret them
> - Can run a linear regression, use it to make predictions, and interpret the coefficients.
> - Can calculate grouped summary statistics using SELECT queries with GROUP BY clauses.

> - Can run a linear regression, use it to make predictions, and calculate performance metrics.
> - Can run a logistic regression, use it to make predictions, and calculate performance metrics.
> - Can run a decision tree classifier/regressor, use it to make predictions, and calculate performance metrics.


## Step 3: Prerequisites

List any prerequisite courses you think your live training could use from. This could be the live session’s companion course or a course you think students should take before the session. Prerequisites act as a guiding principle for your session and will set the topic framework, but you do not have to limit yourself in the live session to the syntax used in the prerequisite courses.

> - [Supervised Learning with scikit-learn](https://learn.datacamp.com/courses/supervised-learning-with-scikit-learn)
> - [Ensemble Methods in Python](https://learn.datacamp.com/courses/ensemble-methods-in-python)



## Step 4: Session Outline

A live training session usually begins with an introductory presentation, followed by the live training itself, and an ending presentation. Your live session is expected to be around 2h30m-3h long (including Q&A) with a hard-limit at 3h30m. You can check out our live training content guidelines [here](_LINK_). 


> _Example from [Python for Spreadsheet Users](https://www.datacamp.com/resources/webinars/live-training-python-for-spreadsheet-users)_
>
> ### Introduction Slides 
> - Introduction to the webinar and instructor (led by DataCamp TA)
> - Introduction to the topics
>   - Discuss need to become familiar with baseline machine learning algorithms
>   - Define what a 'weak' learner is
>   - Discuss learning ensemble methods and go over session outline
>   - Set expectations about Q&A
>
> ### Live Training
> #### Ensemble Technique #1 - `Classifier`
> - Import Diabets classification dataset and print header of DataFrame `pd.read_csv()`, `.head()`
> - Glimpse at the data using `.dtypes`, `.describe()`, `.info()` to understand the data
> - Build baseline models
> - Build layers and first stacked model <u>classifier</u> 
> - Compare baseline and stacked models using `seaborn.boxplot`
> #### Ensemble Technique #2 - `Regressor`
> - Import and briefly explore Abalone regression dataset
> - Build baseline models
> - Build layers and first stacked <u>regressor</u> 
> - Compare baseline and stacked models using `seaborn.boxplot`
> #### Ensemble Technique #3 - `Regressor`
> - Discuss multiple layer stacking
> - Build additional layer and stacked regressor model
> - Compare baseline and stacked models using `seaborn.boxplot`
> - Discuss how to apply same to `sklearn.ensemble.StackingClassifier`
> - **Q&A**
>
> ### Ending slides
> - Recap of what we learned
> - The model stacking mindset
> - Call to action and course recommendations

## Authoring your session

To get yourself started with setting up your live session, follow the steps below:

1. Download and install the "Open in Colabs" extension from [here](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo?hl=en). This will let you take any jupyter notebook you see in a GitHub repository and open it as a **temporary** Colabs link.
2. Upload your dataset(s) to the `data` folder.
3. Upload your images, gifs, or any other assets you want to use in the notebook in the `assets` folder.
4. Check out the notebooks templates in the `notebooks` folder, and keep the template you want for your session while deleting all remaining ones.
5. Preview your desired notebook, press on "Open in Colabs" extension - and start developing your content in colabs _(which will act as the solution code to the session)_.  :warning: **Important** :warning: Your progress will **not** be saved on Google Colabs since it's a temporary link. To save your progress, make sure to press on `File`, `Save a copy in GitHub` and follow remaining prompts. You can also download the notebook locally and develop the content there as long you test out that the syntax works on Colabs as well.
6. Once your notebooks is ready to go, give it the name `session_name_solution.ipynb` create an empty version of the Notebook to be filled out by you and learners during the session, end the file name with `session_name_learners.ipynb`. 
7. Create Colabs links for both sessions and save them in notebooks :tada: 
