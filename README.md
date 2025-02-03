# 🚀 Python RVC Inference Cli

<center>A perfect set of tools for voice cloning, easily and free!</center>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiurobox/python-rvc-cli/blob/main/colab/python_rvc_cli.ipynb)

> [!NOTE]  
> Ths project orgnally by blaisewf. this project only for inference duh

### Installation

Ensure that you have the necessary Python packages installed by following these steps (Python 3.9 is recommended):

#### Windows

Execute the [install.bat](./install.bat) file to activate a Conda environment. Afterward, launch the application using `env/python.exe rvc_cli.py` instead of the conventional `python rvc_cli.py` command.

#### Linux

```bash
chmod +x install.sh
./install.sh
```

### Getting Started

For detailed information and command-line options, refer to the help command:

```bash
python rvc_cli.py -h

python uvr_cli.py -h

python download_audio.py -h
```

This command provides a clear overview of the available modes and their corresponding parameters, facilitating effective utilization of the RVC CLI, but if you need more information, you can check the [documentation](https://rvc-cli.pages.dev/).

### References

The RVC CLI builds upon the foundations of the following projects:

- **Vocoders:**

  - [HiFi-GAN](https://github.com/jik876/hifi-gan) by jik876
  - [Vocos](https://github.com/gemelo-ai/vocos) by gemelo-ai
  - [BigVGAN](https://github.com/NVIDIA/BigVGAN) by NVIDIA
  - [BigVSAN](https://github.com/sony/bigvsan) by sony
  - [vocoders](https://github.com/reppy4620/vocoders) by reppy4620
  - [vocoder](https://github.com/fishaudio/vocoder) by fishaudio

- **VC Clients:**

  - [Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) by RVC-Project
  - [So-Vits-SVC](https://github.com/svc-develop-team/so-vits-svc) by svc-develop-team
  - [Mangio-RVC-Fork](https://github.com/Mangio621/Mangio-RVC-Fork) by Mangio621
  - [VITS](https://github.com/jaywalnut310/vits) by jaywalnut310
  - [Harmonify](https://huggingface.co/Eempostor/Harmonify) by Eempostor

- **Pitch Extractors:**

  - [RMVPE](https://github.com/Dream-High/RMVPE) by Dream-High
  - [torchfcpe](https://github.com/CNChTu/FCPE) by CNChTu
  - [torchcrepe](https://github.com/maxrmorrison/torchcrepe) by maxrmorrison
  - [anyf0](https://github.com/SoulMelody/anyf0) by SoulMelody

- **Other:**
  - [FAIRSEQ](https://github.com/facebookresearch/fairseq) by facebookresearch
  - [FAISS](https://github.com/facebookresearch/faiss) by facebookresearch
  - [ContentVec](https://github.com/auspicious3000/contentvec/) by auspicious3000
  - [audio-slicer](https://github.com/openvpi/audio-slicer) by openvpi
  - [python-audio-separator](https://github.com/karaokenerds/python-audio-separator) by karaokenerds
  - [ultimatevocalremovergui](https://github.com/Anjok07/ultimatevocalremovergui) by Anjok07
  - [yt-dlp](https://github.com/yt-dlp/yt-dlp) by yt-dlp

We acknowledge and appreciate the contributions of the respective authors and communities involved in these projects.
