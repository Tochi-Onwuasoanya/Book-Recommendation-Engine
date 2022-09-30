# Book-Recommendation-Engine
A search engine that recommends books to users using machine learning, cosine similarity, and collaborative filtering. Made with Python and Jupyter Lab.

# What you need
Packages/libraries/languages: <br></br>
Need to have pandas, numpy, python, sckit-learn… installed on your computer in order to run project
Would recommend anaconda and anacoda navigator as well
IDE: 
Pycharm professional, Jupyter Lab, or any ide that supports python and .ipynb files

Data files:
You can download the necessary data from these links:
- goodreads - https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/books
- books_titles.json - https://drive.google.com/file/d/1Iqv9...
- goodreads_interactions.csv - https://drive.google.com/open?id=1zmy...
- book_id_map.csv - https://drive.google.com/uc?id=1CHTAa...
- liked_books.csv




# How to run  
- Download data files 
- Download zip file and unzip to folder of choice. 
- You can then open that folder in ide and then run "jupyter lab" from terminal within ide
- Change directories until you're in the directory where you unzipped the files. Then type jupyter lab in terminal
- You can also copy the files into an ide like pycharm, or jupyter lab, and run the project from there. 
- You can also clone the repo into an ide as well.

*Highly recommend jupyter lab for this project*

When running the project, use the "search.ipynb" file to search for books and their book ids. 

Then create a "likedbooks.csv" file using this template:

https://docs.google.com/spreadsheets/d/1ZT_q6r64qzoqGQ1zoBHcb9oggk9Kv45VP1bdF9kKLnc/edit?usp=sharing

Put your own user id (any number is fine as long as it is the same in every row), the book id you got from "search.ipynb", your rating of the book on a scale of 1-5, and the book title

You can also download a sample liked books csv from:https://drive.google.com/file/d/1dhPh.. (my personal liked books)

Then export and download that file as a csv 

To get recommendations:
- Head to the collaborative_filtering.ipynb file
- Then, run the entire project, starting from the first cell. 

If running in pycharm, wherever a file is read or imported in the code, replace that with the path to the files wherever you downloaded them.
If running in jupyter notebook/lab, then add the files directly to the workspace you're working in. 

Remember to modify the book id's, and search queries in order to make the recommendations personalized for you!!
You can use the search file to help search for book id's, or go on goodreads yourself to get them. 


# Demo 
Click here to watch a demo of the project in Jupyter Notebook


# Next steps
- Make program accesible on the terminal/command line 
- Create front-end in order for users to be able to use the program as a web application
- Try filtering users less or more
- Get more books into liked books
- Try to find more similar users (only took the first 15)
- Try to weight the recommendations by how similar the user was to you (I.e. the more similar they are, the more highly you can value the recommendation)
- Try adjusting the formula
