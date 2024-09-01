# Sound Emotion Recognition

## Project Description
A simple Sound Emotion Recognition classifier using ravsess dataset.The model used to build the classifier is Random Forest

## Streamlit UI 
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install streamlit.

```bash
pip install streamlit
```

## Usage

```python
import foobar

# Adds Title in webpage
st.title("Sound Emotion Recognition App")

#Adds image in webpage
st.image('images used/img_emotion.png')

#Adds widget to upload audio file
st.file_uploader("Upload an audio file", type=["wav", "mp3"])

#Open file at the given location, with fixed audio types
st.audio(audio_file, format='audio/wav')

#Displays test(formatted)
st.write(f"Prediction: {prediction[0]}")

```

## Running ml_app.py

```bash
streamlit run '<your-root-location>'/SIG-AI-HUB/MACHINE_LEARNING_PROJECTS/SUPERVISED_LEARNING_PROJECTS/
Speech_Emotion_Recognition_Random_Forest_Model/ml_app.py

```
## Output Image
![Streamlit interface](./images/Output.png)
 

