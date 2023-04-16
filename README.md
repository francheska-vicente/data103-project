# Project Title
Social media recommendation algorithms are steadily improving—they are nowadays more likely to show content that users will interact with. This is by recommending contents based on the previous interactions of users. However, a disadvantage of this is, what would be the resulting recommendations to a person who is depressed that mostly interacts with depressing content? In the scenario that it would recommend triggering content, what could prevent these recommendations?

Every individual’s life is immeasurable in terms of worth. Depression and suicide are topics that should be taken seriously. More often than not, people focus on the physical being instead of the mental being. For some people, going to professionals and even guidance counselors for mental health concerns are considered taboo or looked down upon. Thus, people may result in posting their thoughts anonymously online as a means to cope with negative thoughts.

The use of social media in this case, Reddit, is part of an individual’s online self-presentation and may paint a bigger picture that cannot be found in a face-to-face setting. After a successful model has been created with the capability to classify text whether it is related to suicide or depression in nature, this study is a supplement to the prevention of suicide and may provide assistance to mental health concerns like depression.

Those individuals that fall into the generated classes can be presented with appropriate suicide prevention Web pages or mental health resources. Additionally, social media algorithms could be prevented in suggesting triggering content to these people. For future studies, suicide prevention and mental health assistance can be improved through the implementation of the results of this project.

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
| [`main.ipynb`](main.ipynb)                      | Main notebook that also holds the Data Cleaning and Pre-processing, and EDA |
| [`ModelingPT1.ipynb`](ModelingPT1.ipynb)        | Notebook that holds the training and tuning of BERT and RoBERTa models      |
| [`ModelingPT2.ipynb`](ModelingPT2.ipynb)        | Notebook that holds the training and tuning of Logistic Regression, Multinomial Naive Bayes, and Random Forest Classifier models      |

#### Comma-separated values (CSV) files
Running the [`main.ipynb`](ToxicComment_S13_Group8.ipynb) notebook will result in the creation of three CSV files. The three CSV files holds the dataset that was used to train the models. However, the main difference of the first two files is the presence of unnecessary character sequences (i.e., hashtags, media links, square brackets, usernames, retweet tags), while the third file is the lemmatized version of the second file.
| CSV files                                    | Description                                                                        |
|----------------------------------------------|------------------------------------------------------------------------------------|
| `cleaned_data.csv`                           | Dataset with unnecessary character sequences                                       |
| `cleaned_data_with_char_seq_removal.csv`     | Dataset without the unnecessary character sequences                                |
| `lemmatized_with_char_seq_removal.csv`      | Lemmatized version of the dataset without the unnecessary character sequences      |

## Trying out the Models
You can try out our trained models in the [`ModelPrediction.ipynb`](ModelPrediction.ipynb) notebook! Note that the Random Forest classifiers are not included in this. 

## Authors
- **Jean Pauline Gozon**  <br/>
- **Gillian Nicole Jamias**  <br/>
- **Andrea Jean Marcelo**  <br/>
- **Anton Gabriel Reyes**  <br/>
- **Francheska Josefa Vicente**  <br/>
