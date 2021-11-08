# transfer-totals
Visualizing European transfer spending

# Data
Original data set courtesy of https://github.com/ewenme/transfers. Data manipulation was done in ```src/data_manipulation.ipynb```, whose output is contained in ```data/cleaned_all_transfers.csv```. The original dataset had duplicate transfers present if a club was selling to another club in the data set (eg. Barcelona to PSG). These duplicates were removed. Cleaned data also has a player ID system based off of player name, position, and age so that visualization avoids lumping different players into the same visual (eg. Adriano).  

# Running this Analysis
To run the interactiver version of this notebook, clone this repository into a local directory. Then run
```
pip install jupyter
pip install numpy
pip install pandas
```
to set up your environment. You will then be able to run 
```
jupyter notebook
```
to launch the notebook server and interact with the notebook.
