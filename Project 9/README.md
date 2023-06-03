# Spam Email Classification

This project focuses on building a machine learning model to classify emails as spam or ham (non-spam). The data used for training the model is sourced from the [SpamAssassin Public Corpus](https://spamassassin.apache.org/old/publiccorpus/).

## Data

The dataset used for this project consists of emails categorized as spam or ham. The emails were downloaded locally from the SpamAssassin Public Corpus website. The dataset is not included in this repository, but you can download it from the provided link.

## Model

The model for spam email classification is implemented in the `Spam_Email_Classification.ipynb` Jupyter Notebook. The notebook contains the code for data preprocessing, feature extraction using TF-IDF, training a Support Vector Machine (SVM) classifier, and evaluating the model's performance.

## Requirements

To run the code in the Jupyter Notebook, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- scikit-learn
- nltk
- BeautifulSoup
- pandas

You can install the required dependencies using pip:


## Usage

1. Download the email dataset from the [SpamAssassin Public Corpus](https://spamassassin.apache.org/old/publiccorpus/) website and place it in the appropriate folder (ham and spam folders).

2. Open the `Spam_Email_Classification.ipynb` notebook using Jupyter Notebook.

3. Run the notebook cells to preprocess the data, train the model, and evaluate its performance.

4. Once the model is trained, you can use it to classify new emails as spam or ham. Modify the provided code snippet in the notebook to test the model on your own email.

## Contact

For any questions or issues related to this project, please feel free to reach out to:

Email: reeniecd@hotmail.com

