# Script to Motion Video Generator

Transform your written scripts into dynamic motion videos with AI-generated visuals and voiceovers using this Python-based tool. Powered by Hugging Face's text-to-video diffusion models, Google Text-to-Speech (gTTS), and Gradio for an interactive UI, this project generates continuous video segments with voiceovers in various styles.

## Features
- **Text-to-Video Generation**: Convert text prompts into short video clips using the `damo-vilab/text-to-video-ms-1.7b` model.
- **Voiceover Integration**: Add audio narration to videos with customizable voice types (Adult Male, Adult Female, Child, Elderly, Professional).
- **Segment Continuity**: Generate multi-segment videos with smooth transitions between segments for a cohesive story.
- **Interactive UI**: Use a Gradio interface to input prompts, scripts, and voice preferences, and preview the generated video.
- **GPU Support**: Optimized for CUDA-enabled GPUs to accelerate video generation.

## Prerequisites
- Python 3.11+
- CUDA-enabled GPU (optional, for faster processing)
- FFmpeg installed on your system
- A Hugging Face account and API token (for accessing the diffusion model)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/script-to-motion-video-generator.git
   cd script-to-motion-video-generator
