# Project Title

## How to set up and run the project locally through JupyterNotebook or JupyterLab
1. Extract the folder from the zipped file that you can download through this DownGit [link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/francheska-vicente/data103-project).
2. Launch `Jupyter notebook` or `JupyterLab`.
3. Navigate to the project folder containing main.ipynb.
4. Open `main.ipynb`. This contains the **data pre-processing** and **cleaning**, the **Exploratory Data Analysis**, and the **model training and tuning** of the best model.

## Project Files and Folders
This Github Repository contains three Jupyter notebooks, and two CSV files.

#### Jupyter Notebooks
| Jupyter notebooks                               | Description                                                                 |
|-------------------------------------------------|-----------------------------------------------------------------------------|
| [`main.ipynb`](ToxicComment_S13_Group8.ipynb)   | Main notebook that also holds the Data Cleaning and Pre-processing, and EDA |
| [`ModelingPT1.ipynb`](ModelingPT1.ipynb)        | Notebook that holds the training and tuning of BERT and RoBERTa models      |
| [`ModelingPT2.ipynb`](ModelingPT2.ipynb)        | Notebook that holds the training and tuning of Logistic Regression, Multinomial Naive Bayes, and Random Forest Classifier models      |

#### Comma-separated values (CSV) files
The two CSV files holds the dataset that was used to train the models. However, their main difference is the presence of unnecessary character sequences (i.e., hashtags, media links, square brackets, usernames, retweet tags).
| CSV files                                                                                | Description                                               |
|-------------------------------------------------------------------------------------------|----------------------------------------------------------|
| [`cleaned_data.csv`](cleaned_data.csv)                                                    | Dataset with unnecessary character sequences             |
| [`cleaned_data_with_char_seq_removal.csv`](cleaned_data_with_char_seq_removal.csv)        | Dataset without the unnecessary character sequences      |
