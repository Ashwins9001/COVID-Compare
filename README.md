# COVID-Compare
Collected groups of related keywords via Gaussian Mixture Model to find trends in America and Canada's responses to the Coronavirus outbreak. 

Implemented Principal Component Analysis to reduce feature (words) dimensionality down to two dimensions for analysis. Displayed sample data (article corpus) into gaussian clusters. Found topics via each cluster containing related words. Used a Mixture of Gaussians to predict distribution and through Estimation-Maximisation (EM) algorithm, adjust mean and covariance parameters per samples of each Gaussian cluster. Improved flexibility to capture more related data and show accurate trends. 

# Technology Used
- BeautifulSoup used for scraping text data from Global News
- Sklearn, Pandas, Numpy, Seaborn used for data handling, visualization
- Data contained in NoSQL MongoDB collection due to unstructured form of keywords, can be queried via leader name (e.g. 'Trump', 'Trudeau')

# Credits
Source code for implementing Gaussian Mixture Model in Python & visualization cluster centroids & shape goes to Daniel Foley via Medium (https://towardsdatascience.com/gaussian-mixture-modelling-gmm-833c88587c7f)
