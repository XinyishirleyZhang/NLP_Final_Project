# NLP_Final_Project

# Predictive Analysis of Fiction Book Reviews Using TF-IDF

## Overview
This project explores the predictive power of Term Frequency-Inverse Document Frequency (TF-IDF) extracted keywords and phrases from fiction book reviews in forecasting user ratings. Utilizing a robust dataset of fiction reviews, this study employs machine learning algorithms, with a particular focus on the Random Forest algorithm, to identify and analyze the linguistic features that most significantly influence reader satisfaction and ratings.

## Repository Contents
- **Notebook (IPYNB)**: Jupyter Notebook containing the full analysis, from data preprocessing to model training and evaluation.
- **PDF Version**: A PDF export of the Jupyter Notebook for those who prefer reading in a non-interactive format.
- **HTML Version**: An HTML version of the Jupyter Notebook, offering an interactive web view.

## Data Access
Due to the large size of the dataset, it was not feasible to upload it directly to this repository. Instead, the dataset can be accessed through the following Google Drive link:
[Google Drive Dataset Link](https://drive.google.com/drive/folders/1ybHzuxki3j1RWNX7JaiaBs7BxRm7E4PI?usp=sharing)

Please download the dataset from this link to fully replicate the analysis presented in the notebooks.

## Data Source
The dataset for this research comprises comprehensive Amazon book reviews, encapsulating both qualitative and quantitative elements that offer insights into consumer behaviors and preferences within the literary market. The `books_data` segment of the dataset presents essential bibliographic information, capturing the title, authorship details, visual and digital book previews, publisher information, publication date, online info links, genres, and reader engagement quantified through ratings counts.

Concurrently, the `books_rating` portion features a granular view of individual consumer feedback, expressed through unique identifiers, profile names, helpfulness of reviews, numeric scores, temporal markers of reviews, summaries, and the complete textual content of the reviews. This multifaceted dataset not only enables a sentiment analysis of textual reviews to assess the emotions and opinions expressed by readers but also facilitates a deeper examination of the factors influencing the numerical scores books receive.

By synthesizing these diverse data points, the study aims to model and predict how sentiment embedded within reviews correlates with the books' overall ratings, offering a predictive lens on how consumer sentiment potentially sways purchasing decisions. This detailed exploration of the dataset will support the research question and enhance the comprehension of the underlying analysis.

For an in-depth overview of the dataset, please refer to the resources provided on Kaggle, which host discussions and downloadable content related to the dataset[Kaggle Discussion](https://www.kaggle.com/discussions/general/354528)

## Project Highlights
- **TF-IDF Analysis**: This project leverages the TF-IDF technique to quantify the importance of words in book reviews relative to their frequency across the corpus, highlighting unique terms that correlate strongly with user ratings.
- **Predictive Modeling**: By employing the Random Forest algorithm, the project assesses the ability of machine learning to predict book ratings based on the extracted features.
- **Evaluation**: The effectiveness of the predictive models is evaluated using various metrics including Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE), providing insights into the models' accuracy and areas for improvement.

## Limitations and Future Work
While the project provides significant insights into the predictive power of textual analysis in literature reviews, it acknowledges limitations such as the handling of outliers and the need for more complex model architectures. Future research directions include the integration of neural networks and sentiment analysis to enhance the understanding and prediction of reader satisfaction.
