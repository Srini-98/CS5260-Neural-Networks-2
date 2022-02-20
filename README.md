# CS5260-Neural-Networks-2
This code repo has the following folders:

- data_collection: Run the notebooks in the path to download the dataset associated with the project https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home and to extract 5000 books and their features.

- dataset: This folder has the relevant image covers of 5000 books and the associated features in the file books_with_genres.csv. Ensure to extract the files from their equivalent tar files using the commands:
```
tar -xvzf images.tar
tar -zvzf books_with_genres.tar
tar -xvzf goodreads_book_genres_initial.tar
```

#### Environment setup
======================
Ensure Anaconda is set up and use the environment.yml in the code repo to set up an environment as follows:
```
conda env create -f environment.yml

conda activate cs5260
```
