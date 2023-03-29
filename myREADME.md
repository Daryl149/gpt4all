# gpt4all

python3 -m venv gpt4all_1 --system-site-packages
source gpt4all_1/bin/activate
python -m pip install -r requirements.txt
# Clone this repository down and download the CPU quantized gpt4all model.
https://the-eye.eu/public/AI/models/nomic-ai/gpt4all/gpt4all-lora-quantized.bin
Place the quantized model in the chat directory and start chatting by running:
cd transformers
pip install -e . 
cd ../peft
pip install -e .
cd ..
cd chat;./gpt4all-lora-quantized-OSX-m1 on M1 Mac/OSX
cd chat;./gpt4all-lora-quantized-linux-x86 on Windows/Linux
