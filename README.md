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
![](https://raw.githubusercontent.com/yerfor/GeneFace/main/assets/GeneFace.png)

[GitHub](https://github.com/MoonInTheRiver/DiffSinger) - Diffsinger - Singing Voice Synthesis via Shallow Diffusion Mechanism
![](https://raw.githubusercontent.com/MoonInTheRiver/DiffSinger/master/resources/tfb.png)

some more examples of Text2Speech models:

- [ttsmms](https://github.com/wannaphong/ttsmms) - Text-to-speech with The Massively Multilingual Speech (MMS) project
- [pyttsx3](https://pypi.org/project/pyttsx3/) - Text to Speech (TTS) library for Python 2 and 3. Works without internet connection or delay. Supports multiple TTS engines, including Sapi5, nsss, and espeak.


## Image
#### Kandinsky
![image](https://raw.githubusercontent.com/ai-forever/Kandinsky-2/main/content/einstein.png)
[GitHub](https://github.com/ai-forever/Kandinsky-2/tree/main/notebooks) - Kandinsky 2.0 - 2.2
You may also find the the code for finetuning ([1](https://github.com/ai-forever/Kandinsky-2/blob/main/notebooks/train_prior.ipynb), [2](https://github.com/ai-forever/Kandinsky-2/blob/main/notebooks/lora_decoder.ipynb)) and [inpainting](https://github.com/ai-forever/Kandinsky-2/blob/main/notebooks/Kandinsky_2_0_inpainting.ipynb) with Kandinsky


[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1MfN9dfmejT8NjXhR353NeP5RzbruHgo7?usp=sharing) - Kandinsky 2.2 Inference example

[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1lUWfe4CWhPJhUZYjMAE7g4ciHX4764rN?usp=sharing) - Kandinsky 2.2 fine-tuning with LoRA


#### IF
A novel state-of-the-art open-source text-to-image model with a high degree of photorealism and language understanding
![](https://raw.githubusercontent.com/deep-floyd/IF/develop/pics/nabla.jpg)
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/deepfloyd_if_free_tier_google_colab.ipynb)

[Kaggle](https://www.kaggle.com/code/shonenkov/deepfloyd-if-4-3b-generator-of-pictures) [GitHub](https://github.com/deep-floyd/IF)

#### Stable Diffusion
![](https://raw.githubusercontent.com/Stability-AI/stablediffusion/main/assets/stable-samples/txt2img/768/merged-0002.png)
[GitHub](https://github.com/Stability-AI/stablediffusion) - This repository contains Stable Diffusion models trained from scratch and will be continuously updated with new checkpoints


#### Superres
[GitHub](https://github.com/boomb0om/generations-pipeline) - Increasing a picture quality by upscaling it with the power of diffusion models


#### StackMix-OCR
[GitHub](https://github.com/ai-forever/StackMix-OCR) - a handwritten text recognition(HTR) system that outperforms current state-of-the-art methods
![](https://camo.githubusercontent.com/49aae1b26fbf96ba2bf87640256141f6c628c5a1bb26b4025ab819bff3257266/68747470733a2f2f73756e392d36342e757365726170692e636f6d2f696d70672f7841466d446e567575546d6334464d5f464b684c506e712d4b767270704434782d4476554b672f687931714b6252625335382e6a70673f73697a653d34303278333035267175616c6974793d3936267369676e3d356264666137373032663265363535636339393165323734643462623762336626747970653d616c62756d)

[![Build Status](https://camo.githubusercontent.com/7038d1559d7306912c5c1d2a8fa1b683464ad48440bc8f4db49038821b373712/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f61725869762d50617065722d253343434f4c4f522533452e737667)](https://arxiv.org/abs/2108.11667) - StackMix and Blot Augmentations for Handwritten Text Recognition


#### ScrabbleGAN
[GitHub](https://github.com/arshjot/ScrabbleGAN) - a semi-supervised approach to synthesize handwritten text images that are versatile both in style and lexicon. ScrabbleGAN relies on a novel generative model which can generate images of words with an arbitrary length. We show how to operate our approach in a semi-supervised manner, enjoying the aforementioned benefits such as performance boost over state of the art supervised HTR. Furthermore, our generator can manipulate the resulting text style. This allows us to change, for instance, whether the text is cursive, or how thin is the pen stroke
![](https://raw.githubusercontent.com/arshjot/ScrabbleGAN/main/graphics/title.png)

[![Build Status](https://camo.githubusercontent.com/7038d1559d7306912c5c1d2a8fa1b683464ad48440bc8f4db49038821b373712/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f61725869762d50617065722d253343434f4c4f522533452e737667)](https://arxiv.org/abs/2003.10557) - Semi-Supervised Varying Length Handwritten Text Generation


## Video

#### Stable Diffusion
https://user-images.githubusercontent.com/14872007/232229730-82df36cc-ac8b-46b3-949d-0e1dfc10a975.mp4

[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1uW1ZqswkQ9Z9bp5Nbo5z59cAn7I0hE6R?usp=sharing#scrollTo=NW1MUCGkqYQz)

[GitHub](https://github.com/kabachuha/sd-webui-text2video) - text2video extension, StableDiffusion WebUI 

#### Text2Video-Zero
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/camenduru/text2video-zero-colab/blob/main/text2video_custom_pro.ipynb)

[GitHub](https://github.com/Picsart-AI-Research/Text2Video-Zero) - Text-to-Image Diffusion Models are Zero-Shot Video Generators

"A horse galloping on a street"
![](https://raw.githubusercontent.com/Picsart-AI-Research/Text2Video-Zero/main/__assets__/github/results/t2v/horse_galloping_2.gif)

#### text2Video 
[GitHub](https://github.com/sibozhang/Text2Video) - Text-driven Talking-head Video Synthesis with Phoneme-Pose Dictionary

#### deforum
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/deforum-art/deforum-stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb)

https://user-images.githubusercontent.com/121192995/224450647-39529b28-be04-4871-bb7a-faf7afda2ef2.mp4

[GitHub](https://github.com/deforum-art/deforum-stable-diffusion) - Deforum Stable Diffusion

[GitHub](https://github.com/deforum-art/sd-webui-deforum) - deforum webui


#### controlnet
[GitHub](https://github.com/lllyasviel/ControlNet) - Adding Conditional Control to Text-to-Image Diffusion Models

[List of colabs](https://github.com/camenduru/controlnet-colab)



## 3D
#### Nerf
![](https://raw.githubusercontent.com/bmild/nerf/master/imgs/pipeline.jpg)
[![Build Status](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/bmild/nerf/blob/master/tiny_nerf.ipynb)

[GitHub](https://github.com/bmild/nerf) - Tensorflow implementation of optimizing a neural representation for a single scene and rendering new views

#### Stable-Dreamfusion
[GitHub](https://github.com/ashawkey/stable-dreamfusion) - A pytorch implementation of the text-to-3D model Dreamfusion, powered by the Stable Diffusion text-to-2D model

https://user-images.githubusercontent.com/25863658/232403162-51b69000-a242-4b8c-9cd9-4242b09863fa.mp4

#### 3DFaceCAM
[GitHub](https://github.com/aashishrai3799/3DFaceCAM)

![](https://raw.githubusercontent.com/aashishrai3799/3DFaceCAM/main/3dfacecam.gif)













