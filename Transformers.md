### Transformers:
 - [link](https://www.youtube.com/watch?v=4Bdc55j80l8)
 -  BERT: - Bidirectional Encoder Representation from tranformers
 -  GPT - generative pre-training
 
 ### Attention mechanism
 -  Attention mechanism has an infinite reference window
 -  RNN has short reference window
 -  LSTM and GRUs have a longer reference window than RNNs
 -  Transformers: --> attention based encoder-decoder architecture
 
 ### architecture of transformers:
 1. Input Embedding : convert words to context vectors
 2. Positional encoding:->  add positional information  to input embeddings (sin, cosine)
 3. Encoder layer:  map all input sequence to an abstract continious representation
      - it has two submodule : attention layer and fully connected layer
      - these two layer has residual connection
  4. multi-head attention module: part of encoder (self attention)
    - self attention : inputs are assosiacted to each other
    - input vectors are passed to  3 linear FC layer Q, K, V
    - Q, K and V are similar to retrival system: 
    - i.e when we give some query to search videos on youtube , it matches with keys i.e video title, descrepton etc. a
    -  Q.V  = score matrix: tells how much focus to put on each words
    -  score matrix is scaled by sqrt(d) : d = dimension of QxK
    -  then take softmax to get attention weights
    -  attention weight x value  == output
   
   5. Decoder: 
    - generate output
    - 
    -  
 
