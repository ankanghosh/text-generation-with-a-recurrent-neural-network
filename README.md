# text-generation-with-a-recurrent-neural-network
Generating text using the Cornell Movie-Dialogs Corpus dataset with a Recurrent Neural Network (RNN).

# About the project
This Google Colab notebook demonstrates text generation using a character-based RNN and the Cornell Movie-Dialogs Corpus dataset. The data undergoes preparation and preprocessing before being used to train an RNN-based model. Training is conducted across Tensor Processing Unit (TPU) cores using TensorFlow’s distributed computing setup for TPUs. Starting with no prior knowledge of English words, the model learns to generate dialogue-like text after training. However, the generated text lacks a high degree of coherence, and potential next steps are identified to enhance the quality and coherence of the outputs.

# Tools Used
Tools and libraries used in this project include convokit, pandas, TensorFlow, and NumPy.

# Who can benefit from the project?
Anyone can use the project to get started with the basics of character-level text generation using TensorFlow.

# Getting Started
Anyone interested in getting started with Machine Learning, Deep Learning, or Natural Language Processing, specifically, character-level text generation with RNNs and TensorFlow, can clone or download the project to get started.

# References
The most important points of reference for the project are as follows.
1. TensorFlow tutorial about using an RNN to generare text. Link [here](https://www.tensorflow.org/text/tutorials/text_generation).
2. Andrej Karpathy's blog about the effectiveness of RNNs. Link [here](https://karpathy.github.io/2015/05/21/rnn-effectiveness/).

# Additional Notes
1. The dataset can be downloaded through ConvoKit using [this](https://convokit.cornell.edu/documentation/movie.html) link. Alternatively, it can be downloaded directly using [this](https://www.cs.cornell.edu/~cristian/Chameleons_in_imagined_conversations.html) link. If the dataset is taken down in the future, please feel free to reach out to me at ankanatwork@gmail.com if you would like to learn more about the data. However, I may not be able to share the dataset with you due to licensing restrictions.
2. The project is a basic one in nature and is not currently being maintained.
3. [Here](https://researchguy.in/text-generation-with-a-recurrent-neural-network-using-tensorflow/) is the blog post covering this work.

