## Representation Learning from Raw data points.
Representation learning attempts to automatically learn good representations of the data from the raw( e.g. sound, characters or words) signals. DL algorithms try to learn multiple levels: starting from simple features to complicated representations. Learned features are easy to adapt, fast to learn. It is some sort of universal learnable framework for representing the world, visual and linguistic information. Differentiable Computers that learn from backpropogating gradients.  

### Word Vectors 

Probably the first task in language understanding is to represent the discrete symbolic representation into
a numerical vectors corresponding to the said symbol that captures not only syntactic structure but also the semantic meaning.

> What is special about human language ? 
> A human language is a system specifically constructed to convey the writer/speaker's meaning
> Not just an environmental signal, it's a deliberate communication.
> Using an encoding which little kids can quickly learn.

A human language is a discrete/symbolic/categorical signalling system.
The symbol is invariant across different encodings. However, a brain encoding appears to be a continuous pattern of activation, and the 
symbols are transmitted via continuous signals of sound/vision.

#### Embedding Space 

> Estimated 13 million tokens for english language but are the all unrelated ? Probably Not !!!

Thus, we would like to represent these tokens into some lower dimension word space that captures all the semantics of the english language. This is where word vectors help us. Just as thought experiment, let's try to solve this problem. How can we do it ? 

###### Heare is a naive way ? The one hot vector

Let's get some notations out of the way. |V| dnotes the size of the vocabulary. \\\( R^{vx1} \\\)
