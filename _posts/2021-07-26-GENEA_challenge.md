---
layout: project
title: GENEA Challenge
permalink: /GENEAchallenge2021/
---


<p align="center">
  <b style="font-size: 48px;"> A large, crowdsourced evaluation of gesture generation systems on common data: The GENEA Challenge 2020 </b>
  <p style="font-size: 32px;"> <a href="https://svito-zar.github.io/">Taras Kucherenko</a>, <a href="http://www.patrikjonell.se">Patrik Jonell</a>,  <a href="https://sites.google.com/view/youngwoo-yoon/">Youngwoo Yoon</a>, <a href="https://www.pieterwolfert.com/"> Pieter Wolfert </a>,  <a href="https://people.kth.se/~ghe/"> Gustav Eje Henter</a> </p>
</p>

<p align="center">
 <a href="https://zenodo.org/record/4094697#.YP69xTqxU5k" style="font-size: 28px; text-decoration: none">[GENEA Workshop'20]  </a>  
 <a style="font-size: 35px; text-decoration: none"> |   </a> 
 <a href="https://dl.acm.org/doi/pdf/10.1145/3397481.3450692" style="font-size: 28px; text-decoration: none">[IUI'21]   </a>   
</p>

<div style="text-align:center"><img src="../assets/2021_GENEA.jpg" alt="GENEA figure" align="middle"></div>

&nbsp;

### ABSTRACT
Co-speech gestures, gestures that accompany speech, play an important role in human communication. Automatic co-speech gesture generation is thus a key enabling technology for embodied conversational agents (ECAs), since humans expect ECAs to be capable of multi-modal communication. Research into gesture generation is rapidly gravitating towards data-driven methods. Unfortunately, individual research efforts in the field are difficult to compare: there are no established benchmarks, and each study tends to use its own dataset, motion visualisation, and evaluation methodology. To address this situation, we launched the GENEA Challenge, a gesture-generation challenge wherein participating teams built automatic gesture-generation systems on a common dataset, and the resulting systems were evaluated in parallel in a large, crowdsourced user study using the same motion-rendering pipeline. Since differences in evaluation outcomes between systems now are solely attributable to differences between the motion-generation methods, this enables benchmarking recent approaches against one another in order to get a better impression of the state of the art in the field. This paper reports on the purpose, design, results, and implications of our challenge.


&nbsp;

***
&nbsp;

### Main video explaining the paper:

<iframe width="660" height="415" src="https://www.youtube.com/embed/QmaoKRzoVwM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

***
&nbsp;

### Additional resources:

[![Synced](https://Svito-zar.github.io/assets/synced.jpg)](https://syncedreview.com/2021/02/10/icmi-2020-best-paper-gesticulator-a-framework-for-semantically-aware-speech-driven-gesture-generation/) 
* - We discovered an issue with the velocity loss implementation used for our experiments. The bug was fixed in [this commit](https://github.com/Svito-zar/gesticulator/commit/11642221751593e801790907b0dd5247d88b6468). The experimental results involving velocity loss were hence not correct and should be disregarded. We are going to conduct a new experiment with the proper velocity loss implementation and will share the results on this project webpage.
* - We have identified a minor error in our paper concerning the results of PCA. The PCA we used had 12 components (as stated), but these accounted for 92% of the variation on the training set, and not 95% like the paper published at ICMI suggests. The error was corrected in online postprints of the article.

&nbsp;

***
&nbsp;

Citation format:
```
@inproceedings{genea2020iui,
author = {Kucherenko, Taras and Jonell, Patrik and Yoon, Youngwoo and Wolfert, Pieter and Henter, Gustav Eje},
title = {A Large, Crowdsourced Evaluation of Gesture Generation Systems on Common Data: The GENEA Challenge 2020},
year = {2021},
isbn = {9781450380171},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3397481.3450692},
doi = {10.1145/3397481.3450692},
booktitle = {26th International Conference on Intelligent User Interfaces},
pages = {11–21},
numpages = {11},
keywords = {evaluation paradigms, conversational agents, gesture generation},
location = {College Station, TX, USA},
series = {IUI '21}
}
```


