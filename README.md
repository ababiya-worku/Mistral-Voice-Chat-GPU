# Mistral-Voice-Chat-GPU
A simple CMD based UI to have a chat with Mistral Voice Chat with a GPU

This project implements a voice chat system using AI language models and text-to-speech capabilities. It supports both Hugging Face and CTransformers models, and can generate audio responses using Microsoft's Edge TTS.

## Features

- Support for multiple AI model formats (GGUF, GGML, Hugging Face models)
- Text-to-speech conversion using Edge TTS
- GPU acceleration (when available)
- Interactive command-line interface

## Dependencies

Before running the script, make sure you have the following dependencies installed:

- Python 3.7+
- PyTorch
- transformers
- edge-tts
- ctransformers

You can install these dependencies using pip:

```
pip install torch transformers edge-tts ctransformers
```

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/ababiya-worku/Mistral-Voice-Chat-GPU.git
   cd Mistral-voice-chat-gpu
   ```

2. Run the script:
   ```
   python Mistaral_voice_chat_gpu.py
   ```

3. When prompted, enter the full path to the directory containing your AI model.

4. If multiple model files are found, you'll be asked to choose one.

5. Enter your prompts when asked. The AI will generate a response, which will then be converted to speech and saved as an MP3 file.

6. Type 'exit' to quit the program.

## Supported Model Formats

- Hugging Face models (.bin, .tar.gz)
- CTransformers models (.gguf, .ggml)

## Download this and place it in any folder you want
## https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.2-GGUF/tree/main

## Notes

- The script will attempt to use GPU acceleration if available.
- Generated audio files are saved in the same directory as the script, with filenames based on your input prompts.
