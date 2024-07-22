

# Movie Recomendation System Using Similarity Matrix


This is the Movie Recomendation System base on content based filtering. Similarity Matrix is used to calculate the similar movie to recommend.



## Authors

- [@smaheshacharya](https://www.github.com/smaheshacharya)



## Package required

 Import Python packages

```bash
  import numpy as np
  import pandas as pd
  import ast
  import nltk
```



    
### Data file

- [@Download](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

### Parameters
```
['movie_id','title','overview','genres','keywords','cast','crew']
```
### Machine Learning Model

```
from sklearn.metrics.pairwise import cosine_similarity
```










### Tech Used

**Client:** Streamlit (Python Framework)

**Server:** Python


## Lessons Learned

Here you will know about how to preprocess movie data and set different paremeter to get result form recommendation system.



## Streamlit Docs
Create project with app.py file.

```
import streamlit as st
import pickle
import pandas as pd
import requests
```

- [@Streamlit Documentation](https://docs.streamlit.io/)



## Screenshots

Recommended movie with respect "Avatar". 

![App Screenshot](https://raw.githubusercontent.com/smaheshacharya/MovieRecomendationSystemUsingSimilarityMatrix/master/movies.png)

Recommended movie with respect "Spider Man 3".

![App Screenshot](https://github.com/smaheshacharya/MovieRecomendationSystemUsingSimilarityMatrix/blob/master/movies_2.png?raw=true)

