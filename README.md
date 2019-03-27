# Generate Simpsons TV Scripts using RNNs

<img src='http://23provincias.com/news/wp-content/uploads/2018/12/thesimpsons-11-all-shows.jpg' align='center' >



Recurrent neural networks RNNs are not limited to be predicteve models for sequential data, they are very successful generative models that can create new plausible sequences for a problem domain, in this particular case the goal is to produce sequences of characters that are similar to The Simpsons TV show. A powerfull type of RNN is called the Long Short-Term Memory LSTM that has performed very effectively when stacked into a deep configuration, achieving state of the art results in many domains like captionning of images and language translation. 

<img src='https://cdn-images-1.medium.com/max/1600/1*O73nlRM3-bWubvt6W-1YSg.png'>

The LSTM uses Back-propagation Through Time and overcomes the vanishing gradient problem, therefore it can be used to create larger RNN that can solve more complex problems. Instead of neurons, LSTMs networks have memory blocks that are connected into layers. A block has components that make it smarter than a classical neuron and a memory for recent sequences, a block contains gages that manage the state and the output, those are:

<img src='https://i.ytimg.com/vi/WCUNPb-5EYI/hqdefault.jpg'>

1. Forget gate: decides what infor discard from the unit.
2. Input gate: decides which values from the input to update the memory.
3. Output gate: decides what to output using the information from the memory and the input.


<img src='https://raw.githubusercontent.com/apolanco3225/Generate-Simpsons-TV-Scripts-using-RNNs/master/tv-script-generation/data/simpsons/script.png' align='center'>


The NN generates a new TV script for The Simpsons TV show using Long Short Term Memories (LSTMs), a recurrent neural network based model for sequential data that is fed with scenes at Moe's Tavern.

