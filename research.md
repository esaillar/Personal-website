---
layout: page
title: Research
permalink: /research/
---



<h3>Research topics</h3>

I am interested in developing tools and methods that aim at **debugging** and **optimizing** HPC applications.

I have developed **PARCOACH**, a static/dynamic tool that detects collective errors in parallel applications. The static part identifies the reduced set of collective communications that may eventually lead to potential deadlock situations,
 and issues warnings. Using this analysis, a selective instrumentation of the code is then achieved, displaying an error, synchronously
 interrupting all processes, if the schedule leads to a deadlock situation. 

PARCOACH is implemented as a **LLVM pass** and is still under development.


<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Grants</h3>
  </div>
  <div class="panel-body">
<td markdown="1">
- <p> <a href="http://www.microcard.eu/index-en.html" target="_blank">Microcard</a>, H2020 (Participant) </p> 
- <p> Plan de relance Inria-Atos </p> 
</td>
  </div>
</div>

<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Former projects</h3>
  </div>
  <div class="panel-body">
<td markdown="1">
- <p> <a href="https://team.inria.fr/cohpc/" target="_blank">COHPC</a> : COrrectness and performance of HPC applications (French PI), Inria associate team (2019 - 2022), 10k€/year </p> 
- <p> Exacard, ANR 2018 (Participant) </p> 
- <p> <a href="http://hacspecis.gforge.inria.fr" target="_blank">HAC SPECIS</a>, Inria project lab on High-performance Application and Computers: Studying PErformance and Correctness In Simulation (2016 - 2020).
</td>
  </div>
</div>

<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Software</h3>
  </div>
  <div class="panel-body">
PARallel COntrol flow Anomaly CHecker (PARCOACH) aims at helping developers in their debugging phase of parallel and distributed applications.

<a href="https://team.inria.fr/storm/software/parcoach/" target="_blank">Read more about PARCOACH</a>
  </div>
</div>



<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
<link href="//netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css" rel="stylesheet">


<div class="panel-group" id="accordion" markdown="1">
 <div class="panel panel-info">
  <div class="panel-heading">
    <h3 class="panel-title"> <a class="accordion-toggle collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapse2"> Talks</a></h3>
  </div>
  <div id="collapse2" class="panel-collapse collapse">
  <div class="panel-body">
<td markdown="1">
- Latest Advancements in PARACOACH for MPI Code Verification, <a href="https://toolsworkshop.hlrs.de/2023/program.html" target="_blank">International Parallel Tools Workshop 2023</a>
- MTV seminar (University of Bordeaux) - 2022
- LLVM pour les nuls, CLAP seminar - 2022
- <a href="http://gpl2018.imag.fr/index.html" target="_blank">Journées nationales du GDR GPL, Grenoble June 12-15, 2018</a>
   Vérification des applications MPI par une anayse statique/dynamique  -  Verification of MPI applications using a static/dynamic analysis (Talk in french)
- <a href="http://tesson.julien.free.fr/LaMHA/2018/" target="_blank">Journée LaHMA, Paris December 13, 2018</a>
   Analyse statique/dynamique pour la vérification des applications parallèles  -  Static/Dynamic Analysis for the verification of parallel applications (Talk in french)

</td>
  </div>
  </div>
  </div>
</div>


<div class="panel panel-danger" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Open Internship Positions (contact me if you are interested)</h3>
  </div>
  <div class="panel-body">
	- None 
  </div>
</div>
