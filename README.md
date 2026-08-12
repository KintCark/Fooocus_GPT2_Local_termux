# Fooocus_GPT2_Local_termux
I figured out you can use fooocus gpt2 model in termux it's awesome I modified the gpt2 code to allow use on termux cli

FIRST INSTALL UBUNTU

1>
pkg update -y && pkg upgrade && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh

2>
apt install update upgrade build-essential python3 python3-dev python3-pip python3-venv git curl ffmpeg libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y

3>
export ANDROID_DATA=anything
export FORCE_CPU=1

4>
pip install diffusers transformers accelerate

5>
python3 (script name).py "a cute cat portrait"


