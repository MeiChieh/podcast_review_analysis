## Podcast Review Analysis

This is an analysis performed on the [Podcast Review Dataset](https://www.kaggle.com/datasets/thoughtvector/podcastreviews/versions/28/data).

Our goal is to perform EDA on the dataset to discover some interesting pattern within the data,
and run hypothesis testing to decide whether the observed pattern is statistically significant.

Analysis notebook access: [Notebook 📚](https://github.com/TuringCollegeSubmissions/mchien-DA.2/blob/master/project.ipynb)

#### Install Dependencies:

```sh
$ pip install -r requirements.txt
$ # if you use pipenv:
$ pipenv install 
```

#### Download Dataset:

If you want to clone and review the project locally,
please download the dataset [here](https://www.kaggle.com/datasets/thoughtvector/podcastreviews/versions/28/data),
unzip and place it in the root folder of this project.

#### Analysis Steps

##### 1. Load & Clean Data

- Connect to SQLite DB
- Detect null/ duplicates
- Detect anomolies
- Cast date data

##### 2. EDA: Podcast category and review distribution

- Podcast category size
- Podcast category rating
- Review rating distribution
- Review rating time series analysis

##### 3. Hypothesis Testing

- Is the the frequency of high-rating significantly lower in morning hours ?
- Is the frequency of highly-rated podcasted significantly less rated in morning hours ?
- Is the frequency of negative-rating-review authors rating more in morning hours ?

##### 4. [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/1de4dc54-9b17-4896-baa4-75c53ceb9e06): Top 10 Most Reviewed Category Comparison Of Morning and Full Hours

- Top 10 most reviewed podcasts
- Proportion of high-rating podcasts in different hours
- Proportion of low-rating authors in different hours
