# NLP machine translation English to Romanian

# Description

The google t5/t5 small model is specified to be used for a machine translation task from English to Romanian. The pretrained model is specified using the Europian Parliament Proceedings of an English-Romanian parallel corpus. 


# Requirements:
Make sure you have the following dependencies installed:

pip install -r requirements.txt


# Usage
The Jupyter notebook can be executed by the command: jupyter execute ass4.4.ipynb.

At the end of the notebook the model is imported using the python line: 

translator = pipeline("translation", model="Translation_model")


The translator can be used by the lines:

text = "translate English to Romanian: " + "This is an example input text."

translator(text)

