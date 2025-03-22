---
title: "Personalized Lightweight Text-to-Speech: Voice Cloning with Adaptive Structured Pruning"
collection: publications
permalink: /publication/2023-06-04-huang2023personalized
authors: '<b>Sung-Feng Huang</b>, Chia-Ping Chen, Zhi-Sheng Chen, Yu-Pao Tsai, Hung-yi Lee
'
excerpt: 'Learnable model pruning for TTS fine-tuning'
date: 2023-06-04
venue: 'IEEE ICASSP'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10097178'
citation: 'Huang, Sung-Feng, Chia-Ping Chen, Zhi-Sheng Chen, Yu-Pao Tsai, and Hung-yi Lee. &quot;Personalized Lightweight Text-to-Speech: Voice Cloning with Adaptive Structured Pruning.&quot; In ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 1-5. IEEE, 2023.'
---

Abstract:
---
Personalized TTS is an exciting and highly desired application that allows users to train their TTS voice using only a few recordings. However, TTS training typically requires many hours of recording and a large model, making it unsuitable for deployment on mobile devices. To overcome this limitation, related works typically require fine-tuning a pre-trained TTS model to preserve its ability to generate high-quality audio samples while adapting to the target speaker’s voice. This process is commonly referred to as &quot;voice cloning.&quot; Although related works have achieved significant success in changing the TTS model’s voice, they are still required to fine-tune from a large pre-trained model, resulting in a significant size for the voice-cloned model. In this paper, we propose applying trainable structured pruning to voice cloning. By training the structured pruning masks with voice-cloning data, we can produce a unique pruned model for each target speaker. Our experiments demonstrate that using learnable structured pruning, we can compress the model size to 7 times smaller while achieving comparable voice-cloning performance.
