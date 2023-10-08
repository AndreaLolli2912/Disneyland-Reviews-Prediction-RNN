# Disneyland Reviews Prediction RNN

This project was created as an assignment for my Machine Learning, Artificial Neural Network, and Deep Learning (2nd module of 2) exam. The aim of this project is to create a model that can infer the rating in terms of how many stars were assigned in a review based on its text. The dataset used is the [Disneyland Reviews dataset](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews), which comprises 42,000 reviews of 3 Disneyland branches - Paris, California, and Hong Kong, posted by visitors on Trip Advisor.

## Project Overview

1. **Data Analysis:** I started the project with an initial data analysis phase, which helped me understand the dataset better and uncover any initial insights.

2. **Data Preprocessing:** After the data analysis, I worked on textual, numerical, and categorical data using various techniques commonly employed in Machine Learning and Natural Language Processing frameworks.

3. **Model Architecture:** The heart of the model consists of a two-layer bidirectional GRUs (Gated Recurrent Units) followed by a classic vanilla neural network. The textual data is fed into the RNN, and its input is flattened and concatenated with the numerical data, forming the input to the neural network for prediction.

4. **Hyperparameter Tuning:** To optimize the model, I conducted a hyperparameter tuning phase, which helped me identify the most suitable parameter values for my model from a predefined range.

5. **Training and Testing:** After training the model, I assessed its performance using unseen data. I visualized the model's performance by creating a confusion matrix to gain insights into its predictive capabilities.

6. **Data Subset:** For this project, I used a small fraction of the available data to reduce time complexity. However, you can choose to use a larger portion of the dataset based on your requirements.

To run the model, it is necessary to download the required files from the following links:

- [Dataset Link](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews)
- [Additional Files](https://drive.google.com/drive/folders/18DakChwcXiTXS-R6aeVZwow5F-s0ZSeB?usp=sharing)

Feel free to explore the code and documentation within this repository to gain a deeper understanding of my approach and findings. If you have any questions or suggestions, please do not hesitate to reach out. Happy modeling!
