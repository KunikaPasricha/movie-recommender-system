This repository consists of 3 files :
First one is a python jupyter notebook file: 
1. The project starts with setting up the jupyter environment and loading the csv dataset of movies and credits in the notebook and converting it into data frame.
2. Extracted all the information from the data and merged both the dataset containing information about movies.
3. All the useful columns are kept and others are removed. In this way, data was converted into very simple format which is easy to read and interpret. So data preprocessing was done.
4. Vectorization of the data
5. Then model is built which would recommend movies based on the input movie provided to it.

After building the model that can make recommendations, we are ready to deploy this model into a website.So the second file 'app' contains the whole code of website development using streamlit.
