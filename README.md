# NER_NLP
by: mohamed fares

The notebook contains code for a Named Entity Recognition (NER) project using spaCy, a popular NLP library. Here's a summary of the main components and functionalities:

Data Loading and Preprocessing: The notebook starts by importing necessary libraries and loading a dataset, which seems to involve words and tags.

Data Inspection and Cleaning: Includes steps for inspecting data, checking for duplicates, and parsing data into sentences, POS tags, and NER tags.

Data Conversion: A function converts the data into a format suitable for spaCy.

Data Splitting: The dataset is split into training, validation, and test sets.

NER Model Setup: A spaCy NER pipeline is set up, including adding labels and creating DocBin for the training data.

Model Training and Saving: The model is trained, fine-tuned, and then saved to disk.

Model Evaluation: The model is evaluated on validation and test datasets, including metrics like confusion matrix and precision-recall curves.

Visualization: Uses spaCy's displacy to visualize entities.
