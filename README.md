# sentiment-analysis-tensorflow-

Data: movie reviews https://github.com/abromberg/sentiment_analysis_python/tree/master/polarityData 

polarity of 1-gram words http://sentistrength.wlv.ac.uk/documentation/language_changes.html


five layer feedforwarding neural network : 

--input layer - four nodes (the total polarity of positive words, the total polarity of neg words, the total number of pos words, the total number of neg words) 

--hidden layers - the number of nodes in these layers regarding to the efficiency of network can be changed 

--output layer - two nodes 



features {
activation function: Relu,
cost function: cross entropy,
optimization method: Adam,
learning_rate=0.001,
batch size = 100,
iterations = 60000 }

