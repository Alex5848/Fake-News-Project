# Fake-News-Project

I split the notebook up in three parts due to reading different parts of the data set for each different notebook. 

The exploration notebook only uses the news samples of 250 rows. 

The chunking notebook is where I used chunking of the csv file to actually analyze the data. This should be run before running the processing notebook, because I'm training models
in the chunking notebook, but I evaluate these models in the processing notebook. I also uploaded the models trained using chunking to the github repository.

The last notebook, the processing notebook, is the main notebook. Here I train my simple models, and models doing in memory learning, which is only learning on 50,000 rows compared to 
the out of core learning where I processed a total of 720*3000 = 2,160,000 rows. 
The evaluating of the models also happen
