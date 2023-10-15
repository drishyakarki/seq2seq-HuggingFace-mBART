# Sequence-to-Sequence mBART from HuggingFace

After implementation of encoders-only and decoders-only transformer models, now is the perfect time to combine the capabilities of both encoders and decoders, also known as Sequence-to-Sequence models. At each stage, the attention layers of the encoder can access all the words in the initial sentence, whereas the attention layers of the decoder can only access the words positioned before a given word in the input.

Sequence-to-sequence models are best suited for tasks revolving around generating new sentences depending on a given input, such as summarization, translation, or generative question answering.

Representatives of this family of models include:

- BART
- mBART
- Marian
- T5

## In this project

In this notebook, I have simply used the power of transformers from the HuggingFace to implement the mBART model for text translation and generation. Here it is a simple basic implementation. Later on in the journey I will be working on much bigger implementations.

## Getting Started
To run this project on your own, follow these steps:

1. Clone the repository.
2. Create a virtual environment using `python -m venv venv`.
3. Install the necessary dependencies using `pip install -r requirements.txt`.

Feel free to explore the code and adapt it to your own projects. Enjoy your NLP journey!

## Creator
Drishya Karki
