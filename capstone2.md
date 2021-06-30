## DSI Capstone 2 Proposal

### Proposal 1 : Mysterious Change No More

Dataset : https://www.kaggle.com/wanderdust/coin-images

* I would use a Convolutional Neural Network on this dataset and predict the value of a pile of coins. 
  * The goals:
    * Can use a picture of a pile of coins to get an estimate of its value (or hopefully use a camera dynamically).
    * Return frequency of each coin. 
  * Possible hurdles : 
    * Since each target is a pile of coins, I might need to make a better dataset, where the feature matrix's data points is an image of a pile. 
    * The target would be the value of the coins. 
    * Unless I find a better way, there might be deficiencies in using edge detection to measure depths from a 2d image (in the case of overlapping coins).               

Note: I want to do this one because it seems fun, but it doesn't seem to have much depth or application to a business-use case. I was thinking of a side-project
      at the very least but would like an outside opinion on it.

### Proposal 2 : Does your newly minted song stand a chance?

Dataset : http://millionsongdataset.com/pages/getting-dataset/#subset

* I intend on using a large dataset of features (such as bars, tempo, etc.) of random songs and generate a model that can predict how well a new song will do.
  * This original dataset is 300 gb large. I will be using a readily available 2.7gb worth of data to generate my feature matrix. 
  * I will webscrape the historical records of Top Song Charts to use as my target matrix. 
  * The goals: 
    * Make a model that can predict how well a song will do on a Top Chart. 
    * Find out which (if any) features are significant in making a hit. 
  * EXTRA : Use web scraping for each song's lyrics and Natural Language Processing to see which ideas/sentiment float to the top of the charts. 

### Proposal 3 : Leukemia Cell Identifier

Dataset : https://www.kaggle.com/andrewmvd/leukemia-classification

* I would build a model that can differentiate between normal cells and myeloblasts(leukemia blast).
  * The goal:
    * A model that can flag worrisome cells a lot faster than a human can.  

(I intend to do all of these eventually, but would like to prioritze the most attractive project to prospective employers.)
