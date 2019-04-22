## Spotmentor Assignment

### Your Task

Make a classifier which takes in a job description and gives the department name for it.

*   Use a neural network model
*   Make use of a pre-trained Word Embeddings (example: Word2Vec, GloVe, etc.)
*   Calculate the accuracy on a test set (data not used to train the model)

### Data Structuring

All the data required can be found in the data folder in the root of the project

There are two sources for loading your training/test data

*   For *Job Description*:  
   **docs** folder contains around 1000 json files, each of which is a single job posting. You have to use the value of `description` field inside the `jd_information` field.

*   For *Job Department*:  
   **document_departments.csv** file contains the mapping of document id to department name where document id is the name of the corresponding file in docs folder.

### Coding Guidelines

**Mandatory**

*   Write your solution code in a jupyter notebook & save it in format YourName_PhoneNumber.ipynb.
*   Make sure to run all cells in notebook before submission.
*   Write clean code & mention comments, steps followed in markdown cells.
*   Update the requirements.txt with all the packages used in your code base.

**Preferable**

*   Adhere to PEP8 formatting
*   Use python 3
*   You can use notebook(YourName_PhoneNumber.ipynb) given in repo as a template.
