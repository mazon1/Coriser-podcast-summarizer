
# Podcast Summarizer using OpenAI and Streamlit

This project is a podcast summarizer that uses OpenAI's API for Automatic Speech Recognition (ASR) and Streamlit for deployment. It allows you to upload a podcast audio file (in M4A format), convert it to text using ASR, and then generate a summary of the podcast transcript.

## Features

- Upload a podcast audio file in M4A format.
- Convert audio to text using OpenAI's ASR API.
- Generate a summary of the podcast transcript.
- Display the original podcast transcript and its summary.

## Getting Started

To run the project locally, follow these steps:

1. Clone this repository to your local machine.

```bash
git clone https://github.com/mazon1/Coriser-podcast-summarizer.git
```

2. Install the required dependencies.

```bash
pip install streamlit openai
```

3. Run the Streamlit app.

```bash
streamlit run app.py
```

4. Upload a podcast audio file in M4A format, click "Convert and Summarize," and view the transcript and summary.

## Project Structure

- `app.py`: Streamlit app code that handles user interface and interaction.
- `README.md`: Project documentation.
- `temp.wav`: Temporary WAV audio file converted from M4A for ASR.

## Usage

1. Upload your podcast audio file (in M4A format) using the file uploader.
2. Click the "Convert and Summarize" button to process the audio and generate a summary.
3. View the original podcast transcript and its summary.

## Additional Notes

- The podcast summarization logic in the `summarize_podcast` function can be customized according to your requirements.
- Make sure to handle any errors that may occur during audio conversion or ASR.

## Dependencies

- [Streamlit](https://www.streamlit.io/)
- [OpenAI](https://platform.openai.com/)
- [torchaudio](https://pytorch.org/audio/stable/index.html)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The OpenAI team for their API services.
- The Streamlit community for the user-friendly app framework.

Feel free to modify and extend this README file to include more details about your project, deployment options, and additional features.
```
