---
layout: project
title: GENEA Challenge 2023
permalink: /GENEAchallenge2023/
---


<p align="center">
  <b style="font-size: 45px;"> The GENEA Challenge 2023: <br/>A large-scale evaluation of gesture generation models in monadic and dyadic settings </b>
</p>
<p align="center" style="font-size: 32px;"> <a href="https://svito-zar.github.io/">Taras Kucherenko</a>, <a href="https://nagyrajmund.github.io/">Rajmund Nagy</a>,  <a href="https://sites.google.com/view/youngwoo-yoon/">Youngwoo Yoon</a>, <a href="https://www.jieywoo.com/"> Jieyeon Woo</a>, <a href="http://teonikolov.com/"> Teodor Nikolov</a>, <a href="https://liahim.net"> Mihail Tsakov</a>, <br/> <a href="https://people.kth.se/~ghe/"> Gustav Eje Henter</a> 
</p>

<p align="center">
 <a href="https://dl.acm.org/doi/pdf/10.1145/3577190.3616120" style="font-size: 28px; text-decoration: none">[conference paper (ICMI 2023)]   </a>   
</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/HleKFkEvCXQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


&nbsp;

### SUMMARY

<p>In the GENEA Challenge 2023 participating teams built speech-driven gesture-generation systems using the same speech and motion dataset, followed by a joint evaluation. This year’s challenge provided data on both sides of a dyadic interaction, allowing teams to generate full-body motion for an agent given its speech (text and audio) and the speech and motion of the interlocutor.12 submissions and 2 baselines were evaluated together with held-out motion-capture data in several large-scale user studies. The studies focused on three aspects: 1) the human-likeness of the motion, 2) the appropriateness of the motion for the agent’s own speech whilst controlling for the human-likeness of the motion, and 3) the appropriateness of the motion for the behaviour of the interlocutor in the interaction in segments where the interlocutor is speaking, using a setup that controls for both the human-likeness of the motion and the agent’s own speech. We found a large span in human-likeness between challenge submissions, with a few systems rated close to human mocap. Appropriateness seems far from being solved, with most submissions performing in a narrow range slightly above chance, far behind natural motion. The effect of the interlocutor is even more subtle, with submitted systems at best performing barely above chance. Interestingly, a dyadic system be- ing highly appropriate for agent speech does not necessarily imply high appropriateness for the interlocutor.</p>


<p>This page collects papers, videos, and other resources from our challenge.</p>


&nbsp;

***
&nbsp;


### Open-source materials:

<div style="text-align:left">
<img style="float: left; border: 6px solid white;" src="../assets/Avatar.jpg" >
<br>
<p style="font-size: 18px;"> Dataset release <a href="https://doi.org/10.5281/zenodo.8199132"> DOI: 10.5281/zenodo.8199132 </a> </p> 
<p style="font-size: 18px;"> User-study video stimuli  <a href="https://doi.org/10.5281/zenodo.8211448"> DOI: 10.5281/zenodo.8211448 </a> </p> 

<p style="font-size: 18px;"> Submitted BVH files <a href="https://doi.org/10.5281/zenodo.8146027"> DOI: 10.5281/zenodo.8146027 </a> </p> 
<br>
<br>
</div>

<div style="text-align:left">
<img style="float: left; border: 6px solid white;" src="../assets/GitHub_logo.png" >
<br>
<p style="font-size: 18px;"> Code for visualising gesture motion  <a href="https://github.com/TeoNikolov/genea_visualizer/"> GENEA visualizer </a> </p> 
<p style="font-size: 18px;"> Code for computing the numerical evaluation metrics <a href="https://github.com/genea-workshop/genea_numerical_evaluations"> GENEA numerical evaluations  </a> </p> 
<br>
<br>
<br>
</div>


<br>
<br>
<br>


&nbsp;

***
&nbsp;

### Citation format:
```
@inproceedings{kucherenko2023genea,
  author={Kucherenko, Taras and Nagy, Rajmund
     and Yoon, Youngwoo and Woo, Jieyeon
    and Nikolov, Teodor and Tsakov, Mihail
    and Henter, Gustav Eje},
  title={The {GENEA} {C}hallenge 2023: {A} large-scale
    evaluation of gesture generation models in
    monadic and dyadic settings},
  booktitle = {Proceedings of the ACM International
    Conference on Multimodal Interaction},
  publisher = {ACM},
  series = {ICMI '23},
  year={2023}
}
```


