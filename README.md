# Fooocus_GPT2_Local_termux
I figured out you can use fooocus gpt2 model in termux it's awesome I modified the gpt2 code to allow use on termux cli

FIRST INSTALL UBUNTU

1>
pkg update -y && pkg upgrade && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh

INSTALLING THIS LONG SETUP WILL MAKE SURE ALL DEPENDS ARE INSTALLED FOR FUTURE APPS FOR TERMUX YOU MIGHT USE 

2>
apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-pip python3-venv python-is-python3 -y && pip install ffmpeg && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0 libsm6 libxrender1 libxext6 -y && apt install libgoogle-perftools-dev && pip install moviepy==1.0.3 && pip install accelerate && pip install setuptools && pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu && apt-get install git-lfs && pip install diffusers && pip install gguf && pip install numba && pip install pynvml && pip install wheel && pip install docutils && pip install use && pip install numpy._utils && pip install fonttools>=4.22.0 && pip install simpleeval && pip install numexpr && pip && pip install insightface && pip install open-clip-torch && pip install einops && pip install cython && pip install polygraphy && pip install torchsde && pip install wget && apt-get install libavformat-dev libavfilter-dev libavdevice-dev ffmpeg && pip install cmake && apt-get install -y build-essential python3-dev python3-setuptools make cmake && pip install omegaconf && pip install pandas && apt install git-lfs && pip install ip_adapter && pip install accelerator && pip install numpy && pip install gradio && pip install transformers diffusers torch huggingface_hub && pip install exiv2 && pip install music-tag && pip install compel && pip install gfpgan && pip install tomesd && pip install peft && pip install 'controlnet_aux' && pip install 'photomaker' && pip install compiler && pip install torchtext==0.15.2 && pip install soundfile && apt install protobuf-compiler libprotobuf-dev && pip install protobuf && pip install ninja && pip install hpsv2 && apt install python3-tk && apt install qtbase5-dev && pip install mistune && pip install dynamicprompts

3>
python3 (script name).py "a cute cat portrait"


