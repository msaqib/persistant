# persistant
Personal Chat Assistant

# How to compile on Windows
1. Create a Python virtual environment by issuing the command `py -3.9 -m venv genai_env`, then activate it `.\genai_env\Scripts\activate`
2. Upgrade pip `.\genai_env\Scripts\python -m pip install --upgrade pip`.
3. Install the core dependencies using:
```pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install transformers>=4.35.0
pip install accelerate
pip install gradio
pip install bitsandbytes```