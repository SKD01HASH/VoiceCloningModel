## Voice Cloning AI Model
To see the full explanation of the code [youtube link](https://youtu.be/L5YNPohALjU)
To run the file with all datasets and other requirements: [Kaggle Link](https://www.kaggle.com/code/saswatakumardashskd/voice-cloning-model-by-saswata-kumar-dash)

### Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Sample Inputs and Outputs](#sample-inputs-and-outputs)
- [Acknowledgements](#acknowledgements)
- [License](#license)
- [Author](#author)

### Overview
The Voice Cloning AI Model, developed by Saswata Kumar Dash, is a cutting-edge solution for voice synthesis. This model is based on the Tacotron2 repository by Ryan Rudes, with significant enhancements and customizations.

This AI model utilizes advanced deep learning techniques to convert text input into natural-sounding audio output. It is built on TensorFlow and leverages a pre-trained Tacotron2 model for transfer learning. Additionally, a custom pickle (pkl) model has been implemented to simplify the saving and loading of trained models.

### Prerequisites
- Python
- TensorFlow
- unidecode
- inflect

### Getting Started
To set up and use the Voice Cloning AI Model, follow these steps:

1. Clone the Tacotron2 repository: `git clone https://github.com/Ryan-Rudes/tacotron2`
2. Navigate to the cloned repository: `cd tacotron2`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the provided code snippets to train the model and generate audio samples.

### Usage
1. Customize the training settings, such as the number of epochs and batch size, in the code snippet provided.
2. Train the model using your own dataset or utilize the existing data to generate audio samples.
3. Adjust the input text and experiment with different phrases and sentences to synthesize audio output.

### Sample Inputs and Outputs
Here are a few examples of input texts and their corresponding synthesized audio outputs:

**Input 1:**
```
"Scientists at the CERN laboratory say they have discovered a new particle."
```
**Output 1:**
(Audio file)

**Input 2:**
```
"The state of Florida reports a surge in coronavirus deaths as restrictions are upended."
```
**Output 2:**
(Audio file)

**Input 3:**
```
"How much wood would a woodchuck chuck if a woodchuck could chuck wood?"
```
**Output 3:**
(Audio file)

Explore the provided code snippets to generate audio samples from various input texts.

### Acknowledgements
I would like to express my gratitude to Ryan Rudes for his invaluable Tacotron2 repository, which served as the foundation for this Voice Cloning AI Model.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Author
Saswata Kumar Dash

For more information and detailed instructions, please refer to the provided code snippets and the [GitHub repository](https://github.com/SKD01HASH/VoiceCloningModel/tree/main).
