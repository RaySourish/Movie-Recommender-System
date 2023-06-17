# Movie-Recommender-System
This Movie Recommender System is an advanced recommendation engine that suggests personalized movie recommendations to users based on their preferences and viewing history. It utilizes content-based filtering techniques and machine learning algorithms to generate accurate and relevant movie recommendations.

## How to run the project?
1.Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
3. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
4. Replace YOUR_API_KEY .
5. Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
6 .Go to your browser and type http://127.0.0.1:5000/ in the address bar.
7 . Get Pandas version<2.0.0
Hurray! That's it.

# Similarity Score
How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuringthe similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

## How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![image](https://github.com/RaySourish/Movie-Recommender-System/assets/78815665/c2e133f7-8d6f-4692-ac30-5d9625305d61)

## Sources of the datasets
1. TMDB
2. IMDB

## After deploying
<img width="949" alt="image" src="https://github.com/RaySourish/Movie-Recommender-System/assets/78815665/bb2a70c6-8ed3-43d6-918f-a1ca6bb43e78">

<img width="949" alt="image" src="https://github.com/RaySourish/Movie-Recommender-System/assets/78815665/b7f42f20-a54a-4cb4-84ac-7e5a6a4eeec6">![Uploading image.png…]()




