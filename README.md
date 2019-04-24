A PyTorch implementation of the Sinusoidal positional encoding/embedding.
In non-recurrent neural networks, positional encoding is used to injects information about the relative or absolute position of the input sequence.
The Sinusoidal-based encoding does not require training, thus does not add additional parameters to the model.
The 1D positional encoding was first proposed in "Attention Is All You Need". This repo implements it as positionalencoding1d.
The 2D positional encoding is an extention to 2D data, e.g., images. It is implemented as positionalencoding2d.
You can find examples and visualization in this notebook.