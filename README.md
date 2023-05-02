# Amazon Best sellers analysis

The goal of this repositorie is to create a classification analysis of amazon sales.

Inside the repository we have three main files, amazon.csv which contains the data, amazon.ipynb which contains the model and finally the pyproject.toml which we can use to install all the dependencies using the ```poetry install``` command.

The model was built using the [Tensorflow Keras](https://keras.io/api/layers/recurrent_layers/lstm/) framework, applying the recurrent neural network algorithm **LSTM** and the text processing module **Tokenizer**.

In addition, basic data mining techniques such as duplicate elimination and data analysis are applied.

On the other hand, the product_category predictor variable was created by defining bestsellers as the top 10% of products sold, and for convenience, the product_name and about_product columns were concatenated into one column.

An accuracy of **91.51%** was achieved by the model.
