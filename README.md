# Engish-French-Translation-ENC_DEC_MODEL
Here we are using a encoder-decoder deep learning architecture to translate english sentences to french. For Encoders we are using LSTMs for understanding the context of the input text. For Decoders too we are using LSTMs for the generation of sequential French words.
# We referred the blog(s):
https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html, 
https://keras.io/examples/nlp/lstm_seq2seq/

![image](https://github.com/user-attachments/assets/35d674e1-bad5-4564-997f-3a8821c841a5)

# ENCODER DECODER ARCHITECTURE:
== In machine learning, an encoder-decoder is a neural network architecture that translates one type of data sequence into another.
== It's made up of two parts: an encoder and a decoder.
== The encoder processes the input sequence to create context vectors, which the decoder then uses to generate the output sequence.
== Encoder-decoder architectures are used in many AI applications, including:
==== Machine translation: For example, Google Translate uses an encoder-decoder structure.
==== Text summarization
==== Image captioning
==== Image generation
==== Image-to-image translation
==== Image compression

The encoder-decoder architecture works by:
1. Capturing information: The encoder accepts a single data element from the input sequence, processes it, and collects information about it.
2. Creating context vectors: The encoder produces a set of context vectors.
3. Generating an output sequence: The decoder uses the context vectors to generate an output sequence. 
The encoder-decoder architecture is trained by optimizing a loss function that measures the difference between the generated output and the target output. The parameters of the encoder and decoder are adjusted to minimize this loss.

![image](https://github.com/user-attachments/assets/ff73844e-5c0b-4cda-bbbc-43d876df3a9a)
