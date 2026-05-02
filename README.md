The goal of this project was to predict the success of the SpaceX Falcon 9 first-stage landing, which is a key factor in reducing launch costs to approximately $62 million per mission.
Data collection was obtained through SpaceX REST API calls and Web Scraping of Wikipedia using BeautifulSoup.
Dataset was cleaned and performed exploratory analysis using SQL to identify launch patterns.
Folium maps was created to analyze site proximity to infrastructure and a Plotly Dash dashboard for real-time success rate filtering.
Four classification models (Logistic Regression, SVM, KNN, and Decision Tree) were trained and tuned using GridSearchCV.
