# Retrieval-based-Voice-Conversion-WebUI

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liujing04/Retrieval-based-Voice-Conversion-WebUI/blob/main/Retrieval_based_Voice_Conversion_WebUI.ipynb)

## Setup
Before training and inferencing, you need these files.

- [hubert_base.pt](https://huggingface.co/lj1995/VoiceConversionWebUI/blob/main/hubert_base.pt)
- [ffmpeg](https://ffmpeg.org/) (make sure `ffmpeg` command is executable yourself)
- `pretrained` directory
- `uvr5_weights` directory 

You can get these files here: https://huggingface.co/lj1995/VoiceConversionWebUI/tree/main

We also provide `RVC-beta.7z` for easy use: [Download](https://huggingface.co/lj1995/VoiceConversionWebUI/blob/main/RVC-beta.7z)

### Setting up Python environment
We recommend you use `venv`.

```sh
$ python -m venv venv
```

```sh
$ pip install -r requirements.txt
```

After that, you can execute `python infer-web.py`.

From our experience, the versions of `librosa`, `numpy` and `numba` are troublesome, but other packages are not so important.

## How to use
Check `小白简易教程.doc`.

Promotional video: https://www.bilibili.com/video/BV1pm4y1z7Gm/

### Realtime Voice Conversion Software using RVC

https://github.com/w-okada/voice-changer
