# PROJECT: Makemore

* `makemore` takes `one text file as input`, where each line is assumed to be one training thing, and `generates more things like it`.
* It is `an autoregressive character-level language model`, with a wide choice of `models from bigrams, MLP all the way to a Transformer` (exactly as seen in GPT), used library `Pytorch`.

Making Everything From Scratch:
* <a href="https://github.com/RustyGrackle/Fundamentals_Of_Machine_Learning/blob/main/Makemore/Back_Propagation_and_Creating_Neuron_Layers_MLP.ipynb">Back Propagation and Creating Neuron, Layers, MLP</a> : In this Notebook, I created `Backpropagation Algorithm` from scratch and created `Neuron`, `layers`, `Multi-layer Perceptron (MLP)` from scratch (A `mini version` of `Pytorch library` from scratch). This is made so, to understand basics of Neural Network and inside the Pytorch library.


## Different Models Used To Make `Makemore`:

* <a
href="https://github.com/RustyGrackle/Fundamentals_Of_Machine_Learning/blob/main/Makemore/BigramLanguageModelling.ipynb">Makemore Project Using Bigram</a> : In this notebook, I have made `Bigram character level language model` from scratch, and then build `Neural Network` using `Pytorch`, which does the same job as `Bigram model`. we have used total `32,033` words to model this.

* <a href="https://github.com/RustyGrackle/Fundamentals_Of_Machine_Learning/blob/main/Makemore/Character_level_Language_Modeling_Using_MLP.ipynb">Makemore Project Using MLP</a> : In this notebook, I have made 'MLP character level language model' from scratch, and `generated new names using 32,033 names`.

* <a href="https://github.com/RustyGrackle/Fundamentals_Of_Machine_Learning/blob/main/Makemore/Makemore_Initialization%2C_Activation%2CGradients%26BatchNorm.ipynb">Initialization, Activation, Gradients & Batch Normalization</a> : (Part1) In this we have talked about how should we initialize our parameters so to get better results from the model.

* <a href="https://github.com/RustyGrackle/Fundamentals_Of_Machine_Learning/blob/main/Makemore/Creating_MLP_using_Pytorch.ipynb">Batch Normalization And Diagnostic Tools Using Pytorch</a> : (Part2) In this we have code our model with `Batch Normalization using Pytorch`. We have also seen some `diagnostic tools` to analyze our model productively. 

* <a href="https://github.com/RustyGrackle/Fundamentals_Of_Machine_Learning/blob/main/Makemore/makemore_part5_wavenet.ipynb">WaveNet Implementation</a> : In this we have implemented WaveNet to optimize our Name Generator model.

--------------------------------------------------------------------------------------------------------------------------------------------
Siddharth Mishra.
