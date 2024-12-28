# Vaani - A Speech-To-Text Summarizer

## Overview
Vaani is a versatile AI-powered tool that integrates **Automatic Speech Recognition (ASR)**, **Translation**, and **Summarization** to process multilingual audio files efficiently. It provides users with transcriptions, translations, and summaries through an interactive web interface.

## Features
- **Speech-to-Text:** Converts audio files into text using state-of-the-art Wav2Vec2 models.
- **Translation:** Translates the transcription into a target language (currently supports English, Hindi, and Malayalam).
- **Summarization:** Generates concise summaries in both the source and target languages.
- **Multi-Language Support:** Supports Hindi and English, with continued improvements on the Malayalam model.
- **User-Friendly Interface:** Built with Gradio for seamless interaction.

## How It Works
1. Upload an audio file (supported languages: Hindi, English, Malayalam{Under Works}).
2. Select the source language and the desired target language for translation.
3. Receive outputs:
   - Transcription of the audio.
   - Translation of the transcription.
   - Summaries in the source and target languages.

## Tech Stack
- **Torch & Transformers:** For running Wav2Vec2 (ASR) and T5 (summarization) models.
- **Librosa:** For preprocessing audio files.
- **Gradio:** Provides an intuitive web-based user interface.
- **Google Colab:** Used for development, testing, and experimentation.

## Installation
### Prerequisites
- Python 3.8 or higher
- Pip installed

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/danybinuluke/Vaani---A-Speech_to_Text_Summarizer.git
   cd Vaani---A-Speech_to_Text_Summarizer
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```
4. Access the Gradio interface through the provided local or public link.

## Models Used
### ASR Models:
- Hindi: `ai4bharat/indicwav2vec-hindi`
- English: `facebook/wav2vec2-large-960h`
- Malayalam: `gvs/wav2vec2-large-xlsr-malayalam`

### Translation Models:
- Hindi to English: `Helsinki-NLP/opus-mt-hi-en`
- Malayalam to English: `ArunIcfoss/mbart-large-50-many-to-many-mmt-ICFOSS-Malayalam_English_Translation`

### Summarization Models:
- Hindi: `google/mt5-base`
- English: `t5-base`
- Malayalam: `ai4bharat/IndicBART`

## Success Rate
Vaani currently achieves a **55% success rate** for transcriptions, translations, and summaries. Ongoing enhancements aim to improve these metrics significantly.


## For Better Interface

After running the Gradio cell, You'll be able to access the Gradio Live server. Please Click on that and Use Vaani on an entire different Tab for better visualisation

## Contributing
Contributions are welcome! If you have ideas for improving Vaani, feel free to fork the repository, make changes, and create a pull request. You can also open issues for bugs or feature requests.

## Feedback
We’re open to suggestions and feedback to make Vaani even better! Please share your thoughts via [GitHub Issues](#) or reach out through [email/contact info].

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For queries or collaborations, please contact:
- **Dany Binu Luke**
- Email: danybinu2005@gmail.com
- LinkedIn: https://www.linkedin.com/in/dany-binu-luke/

---
Thank you for exploring Vaani! 🚀

