# simpson-chatbot
Generative Conversational Chat bot with Seq2Seq Model

A RNN based Seq2Seq Encoder Decoder Model. Trained on dialogue lines from The Simpsons, a popular animated TV series, the model generates a text response when given a user query. From the original > 150k dialog lines, around 18k query-response pairs are retrieved, which is then fed to the model during its supervised training process. Through these qa pairs, a conditional language model can be built to approximate the probability of the next response word token at current timestep, given the query words and generated response word tokens thus far.

## Credits
* Dataset by Pierre Megret (CC BY-SA 3.0): https://www.kaggle.com/pierremegret/dialogue-lines-of-the-simpsons/metadata
* Code adapted from Matthew Inkawhich's Cornell Dialogue Chatbot tutorial https://github.com/MatthewInkawhich/pytorch-chatbot/blob/master/Chatbot_tutorial.ipynb
