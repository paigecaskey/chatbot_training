# Fine-Tuning DialoGPT Medium using LoRA on iMesage Data

## What This Does

Transforms years of your witty texts, embarrassing typos, and 3 AM philosophical rants into a chatbot that talks just like you. It's like having a digital twin, but one that never judges your questionable life choices.

## What's Inside

- **Data Extraction**: SQLite wizardry to mine your iMessage database
- **Text Cleaning**: Removes emojis, URLs, and other digital debris
- **LoRA Fine-tuning**: Memory-efficient training that won't melt your GPU
- **Conversation Formatting**: Teaches the AI proper texting etiquette (yours)
- **Response Generation**: The magic happens here

## Requirements

- Python 3.8+
- PyTorch
- Transformers
- A healthy amount of narcissism
- Years of texting history (the more chaotic, the better)

## Installation

```bash
pip install torch transformers peft datasets pandas scikit-learn huggingface-hub
```

## Technical Details

Built on Microsoft's DialoGPT with LoRA (Low-Rank Adaptation) for efficient fine-tuning. The model learns from your conversation patterns, response styles.
