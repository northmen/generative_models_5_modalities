## Some examples of generative models for 5 different modalities for AIIJC competition
### Text, Music, Image, Video, 3D

This repositiory contains some examples of generative models as a baseline, but it doesn't mean it is the only to generate objects for your scene. This guide could be helpful for those who don't know where to start from.



## Text
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1KyDX_D-rsKN8qpIvo3YMXSYmT3poaBGN) - GPT3.5

```py
Question:
"Чтобы подружиться с осьминогом, нужно: \n1."

The answer:
Чтобы подружиться с осьминогом, нужно: 
1. Взять осьминога в руки.
2. Понюхать его. Если он пахнет тухлой рыбой, то это самка, а если нет - то самец. Самки крупнее самцов и у них более развиты присоски на щупальцах, которыми они удерживают самца во время спаривания. У самки также есть мешочек с яйцами, которые она откладывает в песок. После оплодотворения яйца развиваются в течение нескольких месяцев, пока из них не вылупятся маленькие моллюски. 
3. Пощекотать его под подбородком. Осьминоги очень пугливы, поэтому не стоит делать резких движений, чтобы не спугнуть его и не разозлить. Лучше просто понаблюдать за ним, и он
```


## Music
[GitHub](https://github.com/AIGC-Audio/AudioGPT) - AudioGPT : A whole family of models with sound modality

You may find a lot of examples for Speech, Sing, Audio and even Talking Head on AudioGPT page

[GitHub](https://github.com/MoonInTheRiver/DiffSinger) - Diffsinger - Singing Voice Synthesis via Shallow Diffusion Mechanism


some more examples of Text2Speech models:

- [ttsmms](https://github.com/wannaphong/ttsmms) - Text-to-speech with The Massively Multilingual Speech (MMS) project
- [pyttsx3](https://pypi.org/project/pyttsx3/) - Text to Speech (TTS) library for Python 2 and 3. Works without internet connection or delay. Supports multiple TTS engines, including Sapi5, nsss, and espeak.


## Image
##### Kandinsky
![image](https://raw.githubusercontent.com/ai-forever/Kandinsky-2/main/content/einstein.png)
[GitHub](https://github.com/ai-forever/Kandinsky-2/tree/main/notebooks) - Kandinsky 2.0 - 2.2
You may also find the the code for finetuning ([1](https://github.com/ai-forever/Kandinsky-2/blob/main/notebooks/train_prior.ipynb), [2](https://github.com/ai-forever/Kandinsky-2/blob/main/notebooks/lora_decoder.ipynb)) and [inpainting](https://github.com/ai-forever/Kandinsky-2/blob/main/notebooks/Kandinsky_2_0_inpainting.ipynb) with Kandinsky


[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1MfN9dfmejT8NjXhR353NeP5RzbruHgo7?usp=sharing) - Kandinsky 2.2 Inference example
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1lUWfe4CWhPJhUZYjMAE7g4ciHX4764rN?usp=sharing) - Kandinsky 2.2 fine-tuning with LoRA


##### IF
A novel state-of-the-art open-source text-to-image model with a high degree of photorealism and language understanding
![](https://raw.githubusercontent.com/deep-floyd/IF/develop/pics/nabla.jpg)
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/deepfloyd_if_free_tier_google_colab.ipynb)
[Kaggle](https://www.kaggle.com/code/shonenkov/deepfloyd-if-4-3b-generator-of-pictures) [GitHub](https://github.com/deep-floyd/IF)

##### Stable Diffusion 
![](https://raw.githubusercontent.com/Stability-AI/stablediffusion/main/assets/stable-samples/txt2img/768/merged-0002.png)
[GitHub](https://github.com/Stability-AI/stablediffusion) - This repository contains Stable Diffusion models trained from scratch and will be continuously updated with new checkpoints


##### Superres
[GitHub](https://github.com/boomb0om/generations-pipeline) - Increasing a picture quality by upscaling it with the power of diffusion models






## Video

##### Stable Diffusion
https://user-images.githubusercontent.com/14872007/232229730-82df36cc-ac8b-46b3-949d-0e1dfc10a975.mp4
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1uW1ZqswkQ9Z9bp5Nbo5z59cAn7I0hE6R?usp=sharing#scrollTo=NW1MUCGkqYQz)
[GitHub](https://github.com/kabachuha/sd-webui-text2video) - text2video extension, StableDiffusion WebUI 

##### Text2Video-Zero
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/camenduru/text2video-zero-colab/blob/main/text2video_custom_pro.ipynb)
[GitHub](https://github.com/Picsart-AI-Research/Text2Video-Zero) - Text-to-Image Diffusion Models are Zero-Shot Video Generators

##### text2Video 
[GitHub](https://github.com/sibozhang/Text2Video) - Text-driven Talking-head Video Synthesis with Phoneme-Pose Dictionary

##### deforum
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/deforum-art/deforum-stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb)
[GitHub](https://github.com/deforum-art/deforum-stable-diffusion) - Deforum Stable Diffusion
[GitHub](https://github.com/deforum-art/sd-webui-deforum) - deforum webui

##### controlnet
[GitHub](https://github.com/lllyasviel/ControlNet) - Adding Conditional Control to Text-to-Image Diffusion Models
[List of colabs](https://github.com/camenduru/controlnet-colab)



## 3D
##### Nerf
![](https://raw.githubusercontent.com/bmild/nerf/master/imgs/pipeline.jpg)
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/bmild/nerf/blob/master/tiny_nerf.ipynb)
[GitHub](https://github.com/bmild/nerf) - Tensorflow implementation of optimizing a neural representation for a single scene and rendering new views

##### Stable-Dreamfusion
[GitHub](https://github.com/ashawkey/stable-dreamfusion) - A pytorch implementation of the text-to-3D model Dreamfusion, powered by the Stable Diffusion text-to-2D model


