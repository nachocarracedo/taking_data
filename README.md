# Talking_Data

I had some spare time so I decided to try a new Kaggle comp. I choose "Talking Data" (https://www.kaggle.com/c/talkingdata-mobile-user-demographics) because the data was asking to be stored in sparse matrices and I wanted to gain some experience with this.  

Heads up I didn't have much time to work on the competition itself but I really learnt a lot about sparse matrices and how to construct them.  

There are 2 notebooks on this projects:
* EDA_Taking_Data.ipynb: EDA.
* ml_taking_data.ipynb: Where the data is cleaned, aggregated, and predictions are made.  
 
The use of sparse matrices was a no brainer for me because of the size of the data (my low memory computer also had something to do with it) and how the data was presented.  

The data had devices (cell phones) and the apps that were installed on them. I did one hot encoding on a sparse matrix. Once I had the sparse matrix I do my first predictions. On a second prediction layer I use the probabilities obtained from the first layer and other generated.  

Project is not finished. TO DO list:
* Add comments to walk the reader through the project.  
* 
Enjoy!

