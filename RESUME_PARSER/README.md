# RESUME_PARSER
# Resume Data Annotation and NER Model Training
This Python script is designed to train a Named Entity Recognition (NER) model using spaCy on resume data annotated with entities. It loads annotated training data from a pickle file, initializes a blank English spaCy model, adds the NER pipeline, and trains the model on the annotated data. Finally, it saves the trained model to disk for later use.

# Features:

1. **Data Loading**: Loads annotated training data from a pickle file containing resume data with annotated entities.

2. **Model Initialization**: Initializes a blank English spaCy model and adds the NER pipeline to it.

3. **Training**: Trains the NER model on the annotated training data for a specified number of iterations.

4. **Model Saving**: Saves the trained NER model to disk for future use.

5. **Prediction**: Demonstrates the use of the trained model by applying it to a sample resume data and printing the detected entities.


# How to Use:
1. **Data Preparation**: Annotate resume data with entities of interest and save it in a pickle file format.

2. **Clone the Repository**: Clone or download the repository containing the Python script.

3. **Install Dependencies**: Install the required dependencies such as spaCy and PyMuPDF.

4. **Run the Script**: Execute the Python script in an environment with access to the annotated training data file.

5. **Model Evaluation**: Evaluate the trained model's performance and make adjustments as necessary.


# Dependencies:
Python 3.x

spaCy

PyMuPDF


# Contributors:
Neeha Velagapudi
