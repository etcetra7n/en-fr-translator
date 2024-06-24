# English to German Translator

This is the implementation of the original transformer model described by Vaswani et al in the 
paper "Attention is all you need", implemented using tensorflow and keras. It is trained on a 
small dataset consisting of about 150000 English to German sentence pairs. It features all the
elements described in the paper including Mulltihead Attention mechanism, Positional Encoding and
a learning rate scheduler. However due to limitations of computation resources and small size
of dataset, the model currently does not provide accurate translation. But the reader may feel free
to play with the model, suggest any improvements or train the model on a better training dataset
