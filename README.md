# Portfolio

# About

Hi, my name is Wasin. I have a Bachelor of Science (B.S.) degree in Statistics from UC Davis and a minor in Computer Science.

After spending the last year dedicated to studying and practicing my skills, I now have a more varied skill set that spans a wide array of computer languages and technologies. I am proficient with Python, SQL, Power BI, and Excel, as well as many data oriented libraries in Python such as sklearn, TensorFlow, pandas, NumPy and Seaborn.

This is a repository that I have created to showcase my skills, share projects, and track my progress in Data Analytics / Data Science related topics.

# Projects

In this section I will list my projects, briefly describe them and share my insight and findings.

### Restaurant KPIs Visualized [Link](https://github.com/WasinHongmanee/Sales-Report/blob/main/dashboard.pdf)

**Description:** Using data taken from my family restaurant's POS, I created a dashboard in Power BI to help visualize KPIs and explore data. The KPIs we are concerned with are current and past sales and labor costs. We are also looking for ways to optimize employee hours each day. 

**note:** Data has been manipulated to keep trends but not show real values. Second slide which contained employee work hours and food costs have also been taken out.

**Skills:** data cleaning, data visualization, data analysis

**Worked with:** Power BI, relational databases

**Results:** Used to propose a new data-driven delivery system that can increase revenue by 25% and to improve
employee work hour plans for winter 2022.



### Key Winning Features In League of Legends [Link](https://github.com/WasinHongmanee/League-Win-Predictors)

**Description:** Using the Riot API, I collected events from the first ten minutes of 6661 Challenger ranked games, cleaned the data, summarized the main features using graphs and created a machine learning logistic regression model that predicts the outcome of games with an accuracy of 72.5%. I was able to conclude the top features that point to a winning game using feature selection ranking algorithms.

**Skills:** data extraction using a REST API, data cleaning, data visualization, data analysis, Machine Learning, Normalization of numerical features using MinMaxScaler and Label-Encoding categorical features, Dimensionality reduction and Feature selection

**Worked With:** Python, pandas, SeaBorn, sklearn, REST API, JSON, Jupyter Notebooks

**Results:** The key predictors for game outcome are gold, kill, and experience difference. Winning games have a median difference of 1250 gold, 3 kills and 1000 experience. The original logistic regression model has about a cross validation accuracy mean of .720 while SelectKBest and recursive feature elimination have an accuracy mean of about .725. Both methods agree the other categorical variables are not predictive features.



### Personal Song Recommendation System using Spotify (IN PROGRESS) [Link](https://github.com/WasinHongmanee/SpotifyRecommendation)

**Description:** Given a user selected song on Spotify, return five similar songs from my own music library. Using Spotify's API, I extracted my library of music and 16 numeric features attached with them labeled by Spotify. Some of the features are tempo, acousticness, liveness, key and mode, and popularity. I normalized these features and compare them to the user given song using a measurement called [cosine similarity ](https://en.wikipedia.org/wiki/Cosine_similarity).

**Skills:** data extraction using a REST API, data cleaning, numerical feature normalization using StandardScaler, pairwise-comparison using cosine similarity

**Worked With:** Python, sklearn, pandas, REST API, Jupyter Notebooks

**Current Results:** Similar songs are found, but depending on the genre, it may show a 'similar' song from different genres due to lack of number of songs and variety. Different similarity techniques may be required to quantify how well the song recommendations are.
