# Few-shot face translation ![Source face: Mona Lisa](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/MonaLisa_translation.gif)

A GAN based approach for one model to swap them all. 

The figure below illustrates our priliminary face-swapping results requiring one source face and <=5 target face photos. Notice that almost all of the identities, except Stephen Curry, are not in our training data (which is a subset of [VGGFace2](http://www.robots.ox.ac.uk/~vgg/data/vgg_face2/)). More translation results can be found [here](https://github.com/shaoanlu/fewshot-face-translation-GAN/tree/master/images/translation_results).

Also, our model is capable of producing faces that has its gaze direction, glasses, and hiar occlusions being consistent with given source face. However, our model has suboptimal performance in terms of translating to asian faces. This is possibly due to limited representability of the feature extractor.

|   |[Andrej Karpathy](https://twitter.com/karpathy)|[Andrew Y. Ng](https://twitter.com/andrewyng)|[Du Fu](https://en.wikipedia.org/wiki/Du_Fu)|[Elon Musk](https://en.wikipedia.org/wiki/Elon_Musk)|[Emilia Clarke](https://en.wikipedia.org/wiki/Emilia_Clarke)|[Geoffrey Hinton](https://www.bbc.com/news/technology-47721129)|[Stephen Curry](https://en.wikipedia.org/wiki/Stephen_Curry)|[Yann Lecun](https://research.fb.com/people/lecun-yann/)|[Yoshua Benjio](https://mila.quebec/en/person/bengio-yoshua/)|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **A.K.**|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrejKarpathy01_to_YoshuaBengio.jpg)|
| **A.Y.N**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_AndrejKarpathy.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/AndrewYNg01_to_YoshuaBengio.jpg)|
| **D.F.**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_AndrewYNg.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/DuFu01_to_YoshuaBengio.jpg)|
| **E.M.**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_DuFu.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/ElonMusk01_to_YoshuaBengio.jpg)|
| **E.C.**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_ElonMusk.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/EmiliaClarke05_to_YoshuaBengio.jpg)|
| **G.H.**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_EmiliaClarke.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/GeoffreyHinton01_to_YoshuaBengio.jpg)|
| **S.C.**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_GeoffreyHinton.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_YannLecun.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/StephenCurry01_to_YoshuaBengio.jpg)|
| **Y.L.**|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_StephenCurry.jpg)|N/A|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YannLecun01_to_YoshuaBengio.jpg)|
| **Y.B.**  |![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_AndrejKarpathy.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_AndrewYNg.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_DuFu.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_ElonMusk.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_EmiliaClarke.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_GeoffreyHinton.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_StephenCurry.jpg)|![](https://github.com/shaoanlu/fewshot-face-translation-GAN/raw/master/images/translation_results/YoshuaBengio01_to_YannLecun.jpg)|N/A|
| |<img width=128/>|<img width=128/>|<img width=128/>|<img width=128/>|<img width=128/>|<img width=128/>|<img width=128/>|<img width=128/>|<img width=128/>|

#### I really like the Du Fu translation: such an interesting demostration how the GAN imagine the appearance of the prominent Chinese poet from just a painting.

## Run on Google Colaboratory [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shaoanlu/fewshot-face-translation-GAN/blob/master/colab_demo.ipynb)

###### We only provide pre-trained weights and inference script for now. Training script will be released after code cleanup.

## Architecture
![](https://github.com/shaoanlu/faceswap-GAN-swap-them-all/raw/master/images/few_shot_face_translation_gen.png)

![](https://github.com/shaoanlu/faceswap-GAN-swap-them-all/raw/master/images/few_shot_face_translation_dis.png)

The above image illustrates our generator, which is a encoder-decoder based network, at test phase. Our swap-them-all approach is basically a GAN conditioned on the latent embeddings extracted from a pre-trained face recognition model. [SPADE](https://arxiv.org/abs/1903.07291) and [AdaIN](https://arxiv.org/abs/1905.01723) modules are incorporated in order to inject semantic priors to the networks. 

During training phase, the input face A is heavily blurred and we train the model with resonctruction loss. Other objectives that aimed to improve translation performance while keeping semantic consistency, such as perceptual loss on rgb output and cosine similarity loss on latent embeddings, are also introduced.

### Things that didn't work

1. We tried to distort (spline warp, downsample) the input image as in [faceswap-GAN](https://github.com/shaoanlu/faceswap-GAN) instead of masking it. However, the model did not learn proper identity translation but output face that is similar to its input.

## Requirements
  - Python 3.6
  - Keras 2.2.4
  - TensorFlow 1.12.0 or 1.13.1

## References
1. [Semantic Image Synthesis with Spatially-Adaptive Normalization](https://arxiv.org/abs/1903.07291)
2. [Few-Shot Unsupervised Image-to-Image Translation](https://arxiv.org/abs/1905.01723)
3. [DEEP LEARNING FOR FASHION AND FORENSICS](https://drum.lib.umd.edu/handle/1903/21337)

