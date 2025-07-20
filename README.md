# It's Not Artificial (C'est Pas Artificiel)

## Homage to "C'est pas Sorcier"

This project is an homage to the classic French educational TV show, "[C'est pas Sorcier](https://www.youtube.com/@Cestpassorcierofficiel)". The show was famous for making complex scientific topics simple, engaging, and fun for young audiences.

This script aims to capture that spirit of curious learning by using generative AI.

## 🚀 Description

This Google Colab notebook uses the Google Gemini API to generate a short, educational audio dialogue between two speakers. You can customize the theme, the target age for the content, the language, and even the voices of the speakers.

The script first generates a text transcript where one speaker asks questions and the other, an expert, provides clear answers.

It then uses a multi-speaker text-to-speech model to create a high-quality audio file of the conversation, bringing the educational script to life.

## ✨ Features

- **Dynamic Content Generation**: Creates educational dialogues on any theme you can imagine, from black holes to MLOps.
    
- **Multi-Speaker Audio**: Leverages Gemini's advanced multi-speaker Text-to-Speech capabilities for a natural-sounding and engaging conversation.
    
- **Highly Customizable**: Easily change the parameters in the "Settings" section of the notebook to tailor the output.

## ⚙️ How to Use

1. **Open in Google Colab**: Click the "Open In Colab" badge at the top of this README.
    
2. **Add Your API Key**: You will need a Google Gemini API Key. You can get one for free from [Google AI Studio](https://aistudio.google.com/).
    
    - In the Colab notebook, find the `API_KEY` field and paste your key into the quotes.
        
3. **Adjust the Settings**: Modify the parameters like `THEME`, `AGE`, and `LANG` to fit your needs.
    
4. **Run the Notebook**: Execute the cells in order from top to bottom. The final cell will generate and play the audio file.
    
## 🔧 Settings

You can customize the following parameters at the top of the notebook:

- `API_KEY`: Your secret Google Gemini API key.
    
- `AGE`: The target age for the content, which influences the complexity of the dialogue.
    
- `LANG`: The language of the dialogue (currently supports "English" or "French").
    
- `THEME`: The scientific or technical topic for the conversation.
    
- `MINUTES`: The approximate length of the generated audio dialogue.
    
- `SPEAKER_1_NAME` / `SPEAKER_2_NAME`: The names of the two speakers in the transcript.
    
- `SPEAKER_1_VOICE` / `SPEAKER_2_VOICE`: The pre-built voice models to use for each speaker.
    
- `TRANSCRIPT_MODEL`: The Gemini model used for generating the text.
    
- `TEXT_TO_SPEECH_MODEL`: The Gemini model used for generating the audio.
