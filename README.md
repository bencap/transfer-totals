# transfer-totals
Visualizing European transfer spending

# Data
Original data set courtesy of https://github.com/ewenme/transfers. Data manipulation was done in ```src/data_manipulation.ipynb```, whose output is contained in ```data/cleaned_all_transfers.csv```. The original dataset had duplicate transfers present if a club was selling to another club in the data set (eg. Barcelona to PSG). These duplicates were removed. Cleaned data also has a player ID system based off of player name, position, and age so that visualization avoids lumping different players into the same visual (eg. Adriano).  
