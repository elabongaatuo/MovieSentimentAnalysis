# The BookThief Sentiment Analysis
## Positive or Negative? In this Jupyter NoteBook, I go about mining the tone of sentiments shared by reviewers about one of my favorite movies: The Book Thief

# Introduction
The Book Thief is a deeply captivating movie that I think many haven't heard the chance to experience/ watch. I think it's greatly underrated and a great movie. Naturally, I was curious to see what reviewers' thought of it.I tried to understand people's sentiment towards the movie, an adaptation of the book my Markus Zusak. In this project, I carried out Bilinear Logistic Regression to mine  the tone of sentiments shared by reviewers : positive or negative.

# Project Flow
* Obtain labelled training data from Kaggle
* Define a cleaning function for text cleaning
* Choose a model(Bilinear Logistic Regression), split the data into test and train data
* Build and train the model
* Scrape the BookThief Reviews from IMDB
* Predict the polarity of the reviews


# User Instruction
The project was executed in a Jupyter Notebook using Python. You may fork this repo and use requirements.txt to install the required packages using the following command in the terminal.

``` pip install -r requirements. ```

Be careful not to make too many requests at a particular website of choosing. Your IP address may get blocked. Also please inspect the robots.txt of your choice website before scraping, to see what you can and cannot do. 

Say target website is www.example.com , inspect the robots.txt by typing www.example.com/robots.txt in the search bar.

# Author
Elabonga Atuo 
Reach out to me here : [Email](elabongaatuo@gmail.com)

# Known Issues
Only scraped 25 reviews from IMDB.com instead of all 384 reviews for the BookThief. Well, I got a bit too excited and made so many requests at once a while back and had my IP blocked. 
I will be back with a tutorial on how to rotate proxy IPs and rotate user agents in BeautifulSoup and requests. :)

# Resources and References
1. Understand NLP - [Simplilearn](https://you.tube/CMrHM8a3hqw)
2. What is Sentiment Analysis? - [TechTarget](https://www.techtarget.com/searchbusinessanalytics/definition/opinion-mining-sentiment-mining)
3. Logistic Regression -[MLU-Explain](https://mlu-explain.github.io/logistic-regression/)

# Files
1. labeledTrainData.tsv - Labelled Training Data Used in training the binary logistic model The data was obtained from [Kaggle](kaggle.com/datasets)
2. BookThiefSentimentAnalysis.ipynb - This file contains Python code that goes about explaining how the project was executed.

