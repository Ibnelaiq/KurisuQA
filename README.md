# Makise Kurisu's Responses in Steins Gate VN

This repository contains a collection of Makise Kurisu's responses to various questions in the Steins Gate visual novel. These responses are based on the character's personality and behavior in the game and are intended to provide insights into her thoughts and motivations. Whether you're a fan of the game or simply interested in exploring Kurisu's character, this repository is a valuable resource.

The dataset is intended for use in natural language processing and machine learning projects.

## Contents

The dataset includes a Python file, data.py, which contains the dataset in the form of a Python dictionary. The dictionary is structured like this:
```
data = {
    'Ah...': [
        'Could you come with me for a moment?',
        '...',
        'What about modifying it to send crazy waves or something?',
        'Christina. Are you an @channe--',
        ...
    ],
    "Y-you're with the Organization!?": [
        'Huh?'
    ],
    # more key-value pairs here...
} 
```
This will print the list of strings associated with the question (key) in the data dictionary.

## Usage

You are free to use this dataset for any non-commercial purpose, provided that you give credit to the original source. If you use this dataset in a project, I would appreciate it if you could provide a link back to this repository.

To get started, import the data dictionary from VNresponses.py into your Python code:

```
from data import data

question = 'For my brain has recorded you as my assistant, Christina, and I cannot correct it! MUHAHAHAHA!'; 

responses =  data[question]

print(responses)

# [
#   "I'm gonna crack your skull open and stick electrodes in your hippocampus.",
#   'Who are you talking to?'
# ]

```
###  Credits

This dataset was created by Ahmed Ali and is based on the Steins Gate visual novel created by 5pb. and Nitroplus.

## License

MIT

### Contributions

I welcome contributions to this dataset! If you have additional question-answer pairs to add, please submit a pull request.

