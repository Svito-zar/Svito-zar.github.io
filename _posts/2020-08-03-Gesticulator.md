---
layout: project
title: Gesticulator
permalink: /gesticulator/
---


<p align="center">
  <b style="font-size: 42px;"> Gesticulator:</b>
  <b style="font-size: 42px;"> A framework for semantically-aware speech-driven gesture generation </b>
  <p style="font-size: 28px;" align="center"> <a href="https://svito-zar.github.io/">Taras Kucherenko</a>, <a href="http://www.patrikjonell.se">Patrik Jonell</a>, <a href="https://svanwaveren.wordpress.com">Sanne van Waveren</a>, <a href="https://people.kth.se/~ghe/">Gustav Eje Henter</a>, Simon Alexanderson, <a href="https://iolandaleite.com">Iolanda Leite</a>, <a href="http://www.csc.kth.se/~hedvig/">Hedvig Kjellström</a> </p>
  <p style="font-size: 24px;" align="center"> International Conference on Multimodal Interaction (ICMI '20) </p>
  <p style="font-size: 24px;" align="center"> BEST PAPER AWARD </p>
</p>

<p align="center">
 <a href="../papers/Gesticulator_ICMI_2020.pdf" style="font-size: 30px; text-decoration: none">[Paper]   </a>  
 <a href="https://github.com/Svito-zar/gesticulator" style="font-size: 30px; text-decoration: none">   [Code]</a>   
 <a href="https://figshare.com/projects/Gesticulator/87128" style="font-size: 30px; text-decoration: none">   [Experimental Data]</a>   
</p>

&nbsp;


<iframe width="660" height="415" src="https://www.youtube.com/embed/VQ8he6jjW08" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


&nbsp;

***
&nbsp;

### ABSTRACT
During speech, people spontaneously gesticulate, which plays a key role in conveying information. Similarly, realistic co-speech gestures are crucial to enable natural and smooth interactions with social agents. Current data-driven co-speech gesture generation systems use a single modality for representing speech: either audio or text. These systems are therefore confined to producing either acoustically-linked beat gestures or semantically-linked gesticulation (e.g., raising a hand when saying &ldquo;high&rdquo;): they cannot appropriately learn to generate both gesture types. We present a model designed to produce arbitrary beat and semantic gestures together. Our deep-learning based model takes both acoustic and semantic representations of speech as input, and generates gestures as a sequence of joint angle rotations as output. The resulting gestures can be applied to both virtual agents and humanoid robots. Subjective and objective evaluations confirm the success of our approach.


<div style="text-align:center"><img src="../assets/gest_small.png" alt="portrait" align="middle"></div>


&nbsp;

***
&nbsp;

### Additional resources:
1. Video samples from the ablation study [DOI: 10.6084/m9.figshare.13055609](https://doi.org/10.6084/m9.figshare.13055609)
2. 3D coordinates from the ablation study [DOI: 10.6084/m9.figshare.13055597](https://doi.org/10.6084/m9.figshare.13055597)
3. BVH files from the ablation study [DOI: 10.6084/m9.figshare.13603202](https://doi.org/10.6084/m9.figshare.13603202)
4. Ablation user study results [DOI: 10.6084/m9.figshare.13055585](https://doi.org/10.6084/m9.figshare.13055585)

5. Video samples from the baselining study [DOI: 10.6084/m9.figshare.13061294](https://doi.org/10.6084/m9.figshare.13061294)
6. 3D coordinates from the baselining study [DOI: 10.6084/m9.figshare.13061270](https://doi.org/10.6084/m9.figshare.13061270)
7. BVH files from the baselining study [DOI: 10.6084/m9.figshare.13603169](https://doi.org/10.6084/m9.figshare.13603169)
8. Baselining user study results [DOI: 10.6084/m9.figshare.13061249](https://doi.org/10.6084/m9.figshare.13061249)

&nbsp;

***
&nbsp;

### Erratum:
* - We discovered an issue with the velocity loss implementation used for our experiments. The bug was fixed in [this commit](https://github.com/Svito-zar/gesticulator/commit/11642221751593e801790907b0dd5247d88b6468). The experimental results involving velocity loss were hence not correct and should be disregarded. We are going to conduct a new experiment with the proper velocity loss implementation and will share the results on this project webpage.
* - We have identified a minor error in our paper concerning the results of PCA. The PCA we used had 12 components (as stated), but these accounted for 92% of the variation on the training set, and not 95% like the paper published at ICMI suggests. The error was corrected in online postprints of the article.

&nbsp;

***
&nbsp;

### Press
[![KTH News](https://Svito-zar.github.io/assets/KTH.jpg)](https://intra.kth.se/en/eecs/aktuellt-pa-eecs/nyheter/grattis-till-vinsten-av-best-paper-awards-1.1027836)   [![Stockholm AI](https://Svito-zar.github.io/assets/StockholmAI.jpg)](https://mailchi.mp/stockholm/ai-sweekly-14)

&nbsp;

***
&nbsp;

Citation format:
```
@inproceedings{kucherenko2020gesticulator,
  title={Gesticulator: A framework for semantically-aware speech-driven gesture generation},
  author={Kucherenko, Taras and Jonell, Patrik and van Waveren, Sanne and Henter, Gustav Eje and Alexanderson, Simon and Leite, Iolanda and Kjellstr{\"o}m, Hedvig},
  booktitle={Proceedings of the ACM International Conference on Multimodal Interaction},
  year={2020}
}
```
