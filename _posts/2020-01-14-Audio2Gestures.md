---
layout: project
title: Audio2Gestures
permalink: /audio2gestures/
---


<p align="center">
  <b style="font-size: 45px;"> Aud2Repr2Pose: Analyzing input and output representations for speech-driven gesture generation </b>
  <p style="font-size: 32px;"> <a href="https://svito-zar.github.io/">Taras Kucherenko</a>, <a href="https://hasegawadai.info/">Dai Hasegawa</a>,  <a href="https://people.kth.se/~ghe/">Gustav Eje Henter</a>, <a href="https://scholar.google.com/citations?user=pt6aqHQAAAAJ&hl=ja">Naoshi Kaneko</a>, <a href="http://www.csc.kth.se/~hedvig/">Hedvig Kjellström</a> </p>
</p>

<p align="center">
 <a href="http://www.ifaamas.org/Proceedings/aamas2019/pdfs/p2072.pdf" style="font-size: 35px; text-decoration: none">[AAMAS'19]  </a>  
 <a style="font-size: 35px; text-decoration: none"> |   </a> 
 <a href="https://dl.acm.org/doi/10.1145/3308532.3329472?cid=99659309831" style="font-size: 35px; text-decoration: none">[IVA'19]   </a>  
 <a style="font-size: 35px; text-decoration: none"> |   </a> 
 <a href="https://www.tandfonline.com/doi/full/10.1080/10447318.2021.1883883" style="font-size: 35px; text-decoration: none">   [IJHCI'21]</a>   
</p>

<p align="center">
 <a href="https://github.com/GestureGeneration/Speech_driven_gesture_generation_with_autoencoder" style="font-size: 35px; text-decoration: none">   Code</a>   
</p>

<div style="text-align:center"><img src="../assets/ProposedNew.png" alt="portrait" align="middle"></div>

&nbsp;

### ABSTRACT
This paper presents a novel framework for speech-driven gesture production, applicable to virtual agents to enhance human-computer interaction. Specifically, we extend recent deep-learning-based, data-driven methods for speech-driven gesture generation by
incorporating representation learning. Our model takes speech as input and produces gestures as output, in the form of a sequence of 3D coordinates. 

We provide an analysis of different representations for the input (speech) and the output (motion) of the network by both objective and subjective evaluations. We also analyse the importance of smoothing of the produced motion. 

Our results indicated that the proposed method improved on our baseline in terms of objective measures. For example, it better captured the motion dynamics and better matched the motion-speed distribution. Moreover, we performed user studies on two different datasets. The studies confirmed that our proposed method is perceived as more natural than the baseline, although the difference in the studies was eliminated by appropriate post-processing: hip-centering and smoothing. We conclude that it is important to take both motion representation and post-processing into account when designing an automatic gesture-production method.


&nbsp;

***
&nbsp;

Main video explaining the paper:

<iframe width="660" height="415" src="https://www.youtube.com/embed/Iv7UBe92zrw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

***
&nbsp;

Below is a demo applying that model to a new dataset (which is in English).
To reproduce the results you can use our [pre-trained model](https://github.com/Svito-zar/speech-driven-hand-gesture-generation-demo)

<iframe width="660" height="415" src="https://youtube.com/embed/tQLVyTVtsSU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

***
&nbsp;

Citation format:
```
@inproceedings{kucherenko2019analyzing,
  address={Paris, France},
  author={Kucherenko, Taras and Hasegawa, Dai and Henter, Gustav Eje and Kaneko, Naoshi and Kjellstr{\"o}m, Hedvig},
  booktitle={Proc. IVA},
  doi={10.1145/3308532.3329472},
  keywords={gesture generation, social robotics, representation learning, neural network, deep learning, virtual agents},
  month={July},
  pages={97--104},
  publisher={ACM},
  title={Analyzing Input and Output Representations for Speech-Driven Gesture Generation},
  volume={19},
  year={2019}
}
```


