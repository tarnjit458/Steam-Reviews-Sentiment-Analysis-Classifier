# Steam-Reviews-Sentiment-Analysis-Classifier
CMPE 255 Section 2

Group 2:

Eric Lin

Tarnjit Ghag

Sunny Kohli

### Grabbing the Dataset

Small Data Set
1. Unzip the sample dataset, SteamEnglishReviewSamples.csv file for the code
   - Use this for quick test since dataset is smaller
   - Contains only 100,000 reviews

Full Data Set
1. To run on the full dataset, download the data from https://www.kaggle.com/najzeko/steam-reviews-2021
2. Run Dataset Trimming.ipynb to generate the cut down version of the dataset.


### Running the Classifier Program

1. Use Jupyter notebook to open Steam_Sentiment_Classifier.ipynb
2. If running the small data set, uncomment out  "df = pd.read_csv('SteamEnglishReviewsSample.csv')" and comment out "df = pd.read_csv('SteamEnglishReview.csv')"
   - Skip this step if running full data set
3. Inside Jupyter notebook terminal, run these pip installs:
   "pip install sklearn", "pip install pandas", "pip install numpy", 
   "pip install scipy", "pip install csv", "pip install matplotlib",
   "pip install textblob", "pip install vaderSentiment", "pip install xgboost"
4.  Run all the cells to generate the results
