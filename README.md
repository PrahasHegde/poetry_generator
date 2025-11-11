# Text Generation using LSTM

This project demonstrates how to build and train a text generation model using a Bidirectional LSTM network in TensorFlow/Keras. The model is trained on a corpus of text (specifically, a collection of poems) to learn patterns and generate new text sequences based on a given seed word.

## Project Structure

The project is implemented in a Google Colab notebook and consists of the following steps:

1.  **Import Libraries**: Imports necessary libraries for data manipulation, model building, and visualization.
2.  **Upload Data**: Allows the user to upload the text file (e.g., `poems.txt`) containing the training corpus.
3.  **Load and Explore Data**: Reads the text data, performs basic exploratory data analysis (EDA) by generating a WordCloud, and displays the corpus.
4.  **Tokenize and Sequence Data**: Tokenizes the text data, converts it into sequences of integers, and pads the sequences to a fixed length.
5.  **Build the Model**: Defines a Bidirectional LSTM model using Keras for text generation.
6.  **Train the Model**: Trains the defined model on the prepared data.
7.  **Evaluate the Model**: Displays the training accuracy and loss, and plots the training history.
8.  **Generate Text**: Uses the trained model to generate new text based on a starting seed word.

## Requirements

To run this notebook, you need to have the following libraries installed:

*   `numpy`
*   `pandas`
*   `matplotlib`
*   `tensorflow`
*   `wordcloud`

These libraries are typically pre-installed in Google Colab.

## How to Run

1.  Open the notebook in Google Colab.
2.  Upload your text file (containing the poems or any other text data) when prompted in the "Upload Data" section. Make sure the file name matches the one used in the "Load and Explore Data" cell (`poems.txt` by default).
3.  Run each cell sequentially.

## Generating Text

After training the model, you can generate text by modifying the `seed_text` and `next_words` variables in the "Generate Text" cell and running the cell.
