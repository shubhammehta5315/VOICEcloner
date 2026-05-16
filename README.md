# VOICEcloner

🎙️ VoxCPM2 Multilingual TTS + Voice Cloning for Google Colab.

## Features
- Text-to-Speech
- Voice Design
- Voice Cloning
- Ultimate Cloning
- Gradio UI
- T4 GPU Optimized

## Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubhammehta5315/VOICEcloner/blob/main/VoxCPM2_Gradio_Colab_Blackbox_security.ipynb)



///////////////////////////////////////////////////////////////////////

## One-Click Persistent Setup
from google.colab import drive
import os

print("🔗 Mounting Google Drive...")
drive.mount('/content/drive')

CACHE_DIR = '/content/drive/MyDrive/VOICEcloner_cache'
os.makedirs(CACHE_DIR, exist_ok=True)

os.environ['HF_HOME'] = CACHE_DIR
os.environ['TRANSFORMERS_CACHE'] = CACHE_DIR
os.environ['HUGGINGFACE_HUB_CACHE'] = CACHE_DIR

print(f"✅ Persistent cache enabled: {CACHE_DIR}")
print("🚀 Future launches will be MUCH faster.")

