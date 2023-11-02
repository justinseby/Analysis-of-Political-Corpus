
# Analysis of Political Corpus

**Project Overview**

The "Analysis of Political Corpus" project aims to apply Natural Language Processing (NLP) techniques to gain insights into political debates using the [Political Debates Dataset](http://mpqa.cs.pitt.edu/corpora/political_debates/). This dataset summarizes debates on six prominent US political topics: healthcare, god, guns, Gay Rights, abortion, and creation. Each debate category contains discussion threads, each with discussions presenting either pro or con arguments. The project explores a range of NLP tasks, including text analysis, sentiment analysis, entity recognition, and more, to uncover patterns and insights in the data.

## Project Tasks

The project is organized into several tasks, each focusing on different aspects of the political debates. The tasks are divided into two Jupyter notebooks:

- **Tasks 1 to 4**: Contained in one Jupyter notebook.
  - Download the dataset, organize it for easy manipulation, and save it to an Excel file.
  - Generate statistics on the debates, including the number of threads per category and average message count per thread.
  - Calculate the argument text length and display the distribution.
  - Identify key persons and organizations involved in shaping arguments using SpaCy named-entity recognition.

- **Tasks 5 to 10**: Contained in another Jupyter notebook.
  - Perform sentiment analysis using SentiStrength. Then use Pearson correlation coefficient to test correlation score and its p-value for each category.
  - Assess the relationship between thread and category titles using pre-trained word2vec models.
  - Analyze the coherence of discussion posts within threads using Empath.
  - Examine pro and con reasoning by identifying modal verbs and their context.
  - Test for the presence of negation operators in argument texts and create a histogram showing the percentage of arguments with negation operators.

## How to Use

To run the project tasks, you need Python and Jupyter Notebook installed. Make sure to install the required Python libraries mentioned in the Jupyter notebooks.

1. Clone the repository to your local machine.
2. Open and run the Jupyter notebooks for tasks 1 to 4 and tasks 5 to 10.
3. Follow the instructions and code comments in the notebooks to complete each task.

## Dependencies

The project relies on various Python libraries, including SpaCy, SentiStrength, and more. You can find a list of dependencies in the Jupyter notebooks and the requirements.txt file

