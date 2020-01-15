---
layout: project
title: Audio2Gestures
permalink: /audio2gestures/
---


<p align="center">
  <header>
  <h2> Analyzing input and output representations for speech-driven gesture generation </h2>
  <h3> Taras  Kucherenko,  Dai  Hasegawa, Gustav  Eje  Henter, </h3>
  <h3> Naoshi  Kaneko, and Hedvig Kjellström </h3>
  <h4> International Conference on Intelligent Virtual Agents (IVA '19) </h4>
  </header>
</p>

<p align="center">
 <a href="https://www.researchgate.net/publication/331645229_Analyzing_Input_and_Output_Representations_for_Speech-Driven_Gesture_Generation" style="font-size: 50px; text-decoration: none">Paper</a>    |
 <a href="https://github.com/GestureGeneration/Speech_driven_gesture_generation_with_autoencoder" style="font-size: 50px; text-decoration: none">Code</a>   
</p>


### ABSTRACT
This paper presents a novel framework for automatic speech-drivengesture generation, applicable to human-agent interaction includ-ing both virtual agents and robots. Specifically, we extend recentdeep-learning-based, data-driven methods for speech-driven ges-ture generation by incorporating representation learning. Our modeltakes speech as input and produces gestures as output, in the formof a sequence of 3D coordinates.Our approach consists of two steps. First, we learn a lower-dimensional representation of human motion using a denoisingautoencoder neural network, consisting of a motion encoderMo-tionEand a motion decoderMotionD. The learned representationpreserves the most important aspects of the human pose variationwhile removing less relevant variation. Second, we train a novelencoder networkSpeechEto map from speech to a correspondingmotion representation with reduced dimensionality. At test time,the speech encoder and the motion decoder networks are combined:SpeechEpredicts motion representations based on a given speechsignal andMotionDthen decodes these representations to producemotion sequences.We evaluate different representation sizes in order to find themost effective dimensionality for the representation. We also eval-uate the effects of using different speech features as input to themodel. We find that mel-frequency cepstral coefficients (MFCCs),alone or combined with prosodic features, perform the best. Theresults of a subsequent user study confirm the benefits of the repre-sentation learning

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

