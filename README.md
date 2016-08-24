# taking_data

I had some spare time so I decided to try a Kaggle comp. I choose "Talking Data" (https://www.kaggle.com/c/talkingdata-mobile-user-demographics) because the data was asking to be stored in sparse matrices and I wanted to gain some experience on this.

Heads up I didn't have much time to work on the competition itself but I really learnt a lot about sparse matricess and how to construct them.

There are 2 notebooks:

EDA_Taking_Data.ipynb: Where some EDA is done on the data.
ml_taking_data.ipynb: Where the data is cleaned, aggregated, and predictions are made.

The use of sparse matrices was a no brainer for me because of the size of the data (my low memory computer also had something to do:) ) and how the data was presented. The data had devices (cell phones) and which apps where intalled on them. One hot encoding on a sparse matrix wsas the way to go.
Once I have the sparce matrix I do my first predictions. On a my second prediction layer I use the probabilties obtained from the first layer and other features I generated.

Enjoy!
