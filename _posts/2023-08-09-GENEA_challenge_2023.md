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

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/HleKFkEvCXQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

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

<p style="font-size: 18px;"> Human-likeness user-study results <a href="https://doi.org/10.5281/zenodo.8434117"> DOI: 10.5281/zenodo.8434117 </a> </p> 
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

&nbsp;

***
&nbsp;

<section class="iva-section p-3 p-lg-5 d-flex align-items-center" id="accepted-papers">
                    <div class="w-100">
                        <h2 class="mb-5">Challenge papers</h2>
                    </div>

                        <p>
                        <h4>The FineMotion entry to the GENEA Challenge 2023: DeepPhase for conversational gestures
                            generation
                        </h4>
                        <i>Vladislav Korzun, Anna Beloborodova, Arkady Ilin</i> [<a
                            href="https://openreview.net/forum?id=pVBKLqpAUtP" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3577190.3616119" target="_blank">ACM ICMI</a>]
                        <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>Gesture Motion Graphs for Few-Shot Speech-Driven Gesture Reenactment</h4>
                        <i>Zeyu Zhao, Nan Gao, Zhi Zeng, Guixuan Zhang, Jie Liu, Shuwu Zhang</i> [<a
                            href="https://openreview.net/forum?id=CMivR3x5fpC" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3577190.3616118" target="_blank">ACM ICMI</a>]
                        <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>Diffusion-based co-speech gesture generation using joint text and audio representation</h4>
                        <i> Anna Deichler, Shivam Mehta, Simon Alexanderson, Jonas Beskow</i> [<a
                            href=" https://openreview.net/forum?id=vD3_u_kbkqS" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3577190.3616117" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>


                        <p>
                        <h4>The UEA Digital Humans entry to the GENEA Challenge 2023</h4>
                        <i>Jonathan Windle, Iain Matthews, Ben Milner, Sarah Taylor</i> [<a
                            href="https://openreview.net/forum?id=bBrebR1YpXe" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3577190.3616116" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>FEIN-Z: Autoregressive Behavior Cloning for Speech-Driven Gesture Generation</h4>
                        <i>Leon Harz, Hendric Voß, Stefan Kopp</i> [<a
                            href="https://openreview.net/forum?id=FovoQL3nygw" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3577190.3616115" target="_blank">ACM ICMI</a>]  <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>The DiffuseStyleGesture+ entry to the GENEA Challenge 2023</h4>
                        <i>Sicheng Yang, Haiwei Xue, Zhensong Zhang, Minglei Li, Zhiyong Wu, Xiaofei Wu, Songcen Xu,
                            Zonghong
                            Dai</i> [<a href="https://openreview.net/forum?id=zrcgseqv0n2"
                            target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3577190.3616114" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>Discrete Diffusion for Co-Speech Gesture Synthesis</h4>
                        <i>Ankur Chemburkar, Shuhong Lu, Andrew Feng</i> [<a
                            href="https://openreview.net/forum?id=xPQcKA56N4j" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3610661.3616556" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>The KCL-SAIR team's entry to the GENEA Challenge 2023 Exploring Role-based Gesture
                            Generation in
                            Dyadic Interactions: Listener vs. Speaker</h4>
                        <i>Viktor Schmuck, Nguyen Tan Viet Tuyen, Oya Celiktutan</i> [<a
                            href="https://openreview.net/forum?id=oW4rUGjbMYg" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3610661.3616555" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>Gesture Generation with Diffusion Models Aided by Speech Activity Information</h4>
                        <i>Rodolfo Luis Tonoli, Leonardo Boulitreau de Menezes Martins Marques, Lucas Hideki Ueda, Paula
                            Paro
                            Dornhofer Costa</i> [<a href="https://openreview.net/forum?id=S9Efb3MoiZ"
                            target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3610661.3616554" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>Co-Speech Gesture Generation via Audio and Text Feature Engineering</h4>
                        <i>Geunmo Kim, Jaewoong Yoo, Hyedong Jung</i> [<a
                            href="https://openreview.net/forum?id=mK2qMNf0_Nd" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3610661.3616553" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>DiffuGesture: Generating Human Gesture From Two-person Dialogue With Diffusion Models</h4>
                        <i>Weiyu Zhao, Liangxiao Hu, Shengping Zhang</i> [<a
                            href="https://openreview.net/forum?id=swc28UDR8Wk" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3610661.3616552" target="_blank">ACM ICMI</a>] <br><br>
                        </p>
                        <hr>

                        <p>
                        <h4>The KU-ISPL entry to the GENEA Challenge 2023-A Diffusion Model for Co-speech Gesture
                            generation
                        </h4>
                        <i>Gwantae Kim, Yuanming Li, Hanseok Ko</i> [<a
                            href="https://openreview.net/forum?id=Mm44wlJICIj" target="_blank">OpenReview</a>] [<a
                            href="https://doi.org/10.1145/3610661.3616551" target="_blank">ACM ICMI</a>] <br><br>
                        </p>

</section>


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


