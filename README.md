# Timeline from text input using AI (Beta)
#### This python projects allows you to create a timeline using the Qt python library (to display the timeline) and the ollama API (an AI API to process the text input). You can choose the open source model you like the most from the [ollama model library](https://ollama.com/library) website and change the "model" parameter in the textProcessing.py payload object.
###### _Disclaimer: This version is quite unstable due to the unreliable nature of large language models, so I have also created another version that doesn't use AI [here](https://github.com/tomaszrymaszewski/TimelineMaker).

## Installation
To run this project, in the terminal run ```pip install --requirements``` to install all libraries.

Additionally, go to the ollama website and download their app. Then in your main terminal run the command ```ollama run llama3``` (or the model you like the most from [their library](https://ollama.com/library)). You should be done with the installation then.

## Usage
Run the `main.py` file. You should be able to paste your text. This text should include some events with corresponding dates (the AI is instructed only to display years, not full dates). The model doesn't always work and displays fewer dates on the timeline than are included in the provided text.
