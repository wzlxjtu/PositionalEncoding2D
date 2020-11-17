1D and 2D Sinusoidal positional encoding/embedding (PyTorch)
----
In non-recurrent neural networks, positional encoding is used to injects information about the relative or absolute position of the input sequence.
The Sinusoidal-based encoding does not require training, thus does not add additional parameters to the model.

The 1D positional encoding was first proposed in [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf). This repo implements it in positionalencoding1d.

The 2D positional encoding is an extention to 2D data, e.g., images. It is implemented as positionalencoding2d.
You can find examples and visualization in this [notebook ](https://github.com/wzlxjtu/PositionalEncoding2D/blob/master/visualization.ipynb).

For reference and technical details, please refer to our publication:

- Wang, Zelun, and Jyh-Charn Liu. *"Translating math formula images to LaTeX sequences using deep neural networks with sequence-level training."* International Journal on Document Analysis and Recognition (IJDAR) (2020): 1-13.

