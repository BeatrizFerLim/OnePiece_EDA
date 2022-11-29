# OnePiece_EDA
Exploratory Data Analysis over a Kaggle dataset, containing information from the One Piece episodes.

### Access
The project can be found here: https://github.com/BeatrizFerLim/OnePiece_EDA.

## Used Technologies
* **Python** - The source code is written in Python.
* **Jupyter Notebook** - The platform of choice to implement this project.
* **Python libraries** - Seaborn, Matplotlib, Pandas, and Numpy.

## The Analysis
The analysis performed has a few steps to clean and adjust the dataset:
* Understand the data and each attribute
* Replacement undesirable characters in some of the columns
* Changing the type of some columns, to match their values
* Finding outliers

## Outlier detection
This was based on a few things:
* Find correlations between attributes
* Select those that are not explained by the data itself
* Use Seaborn's Boxplot to find lower and upper limits for attributes that have outliers
* Search the dataset for outliers
* Save them in a different dataframe

## Preview of the analysis
Here is a sample of the dataset after the analysis:

![sample_dataset](https://user-images.githubusercontent.com/46689116/204402053-75255936-0700-4666-a6e4-dea4b8b367ac.png)

Here's the set of outliers found:

![outliers](https://user-images.githubusercontent.com/46689116/204402180-d0ae1a13-68f2-4623-8365-0a6b510b642e.png)

## Conclusion
Through our analysis, we were able to clean and adjust the data to perform a futher investigation: find records that are considered outliers in comparison with the rest of our dataset. This information is important if we have the desire to perfom other analysis. The presence of outliers could impact the results and affect the trustability of our data.

Although this is a small dataset, it was a good training for performing EDA, undestanding the steps and applying the concepts.

A future analysis could be try and build a regression model to predict the 'rank' on other records of the dataset, knowing that the analysis could be tricky with the outliers.
