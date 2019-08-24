# Chatbot with Keras

This is a chatbot I implemented I implemented with the help of [this](https://www.kdnuggets.com/2019/08/deep-learning-nlp-creating-chatbot-keras.html) online article.
It was done using Keras deep learning library.

This paper implements an RNN like structure that uses an attention model to compensate for the long term memory issue prevalent with RNNs.
The RNN structure was implemented from the [paper](https://arxiv.org/pdf/1503.08895.pdf) “End to End Memory Networks” by Sukhbaatar et al.

The Model Architecture:


![alt text](https://github.com/joeljosephjin/chatbot_from_EEMN/blob/master/architecture.png "Logo Title Text 1")


On the left (a) a representation of a single layer of the model. On the right (b) 3 of these layers stacked together.

