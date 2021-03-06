
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fomightez/SynChro-binder/master?filepath=index.ipynb)

# SynChro-binder

tl;dr:  
Click any launch binder badge on this page to use [SynChro software](http://www.lcqb.upmc.fr/CHROnicle/SynChro.html) inside your browser.


-----

***SynChro: reconstruction and visualization of Synteny blocks along Chromosomes.***

SynChro, along with PhyChro,ReChro,and 	
AnChro, is part of the [CHROnicle package](http://www.lcqb.upmc.fr/CHROnicle/) dedicated to the reconstruction of the complete evolutionary history of genomes.

This repository is for running python-based [SynChro software](http://www.lcqb.upmc.fr/CHROnicle/SynChro.html) in a Jupyter environment provided by [MyBinder.org](https://mybinder.org/).  

------


Software
--------

The SynChro software is available directly from the authors at http://www.lcqb.upmc.fr/CHROnicle/SynChro.html.  
The SynChro software is described in two scientific articles [here](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0092621) and [here](http://logcom.oxfordjournals.org/content/23/4/815)([pdf](http://www.lcqb.upmc.fr/CHROnicle/telechargements/JLogicComputation-2011-Drillon-logcom_exr047.pdf)).

Users should cite:

- Drillon G, Carbone A and Fischer G (2014) SynChro: A Fast and Easy Tool to Reconstruct and Visualize Synteny Blocks along Eukaryotic Chromosomes. PLoS ONE 9 (3): e92621. doi:[10.1371/journal.pone.0092621](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0092621)
- Drillon G, Carbone A and Fischer G (2011) Combinatorics of chromosomal rearrangements based on synteny blocks and synteny packs. Journal of Logic and Computation. doi: [10.1093/logcom/exr047](http://logcom.oxfordjournals.org/content/23/4/815) ([pdf](http://www.lcqb.upmc.fr/CHROnicle/telechargements/JLogicComputation-2011-Drillon-logcom_exr047.pdf))

The copyright information for the software is [reprinted below](#license-for-SynChro-software) for clarity.

***Clarifying Software Attribution: I, Wayne, am not involved in the SynChro software at all. Those listed above are the developers and distributors of SynChro. See their materials. I simply set up this repository to make the software useable without installation headaches.***


Usage
-----

This repository is set up to allow running this software after pressing the `launch binder` button above or below.

The notebook that will open upon launch works through the Quick start from [here](http://www.lcqb.upmc.fr/CHROnicle/SynChro.html), plus some it includes some additional visualizations.  It is meant to be worked through in order if you are meaning to actively run it; however, the output from a previous run has been left to allow for some quick assessments of what the software does. Though there is an issue with the graphics if you are just trying to view the previously-generated output, and it may just be easier to view the static rendering available [here](https://nbviewer.jupyter.org/github/fomightez/synchro-binder/blob/master/index.ipynb).

At the bottom of the notebook several vector graphics (`SVG`) files should be rendered when it is run actively; however, because that involves running code, by default they are not rendered when the notebook is reopened, as discussed [here](https://github.com/jupyter/notebook/issues/3038). If you'd like those to be rendered in the active notebook upon opening without needing to trigger the code to actually run in the session, just click the `Not Trusted` badge in the upper right side of the notebook to toggle it to `Trusted`. The graphics should be rendered at this point without the need for triggering any code to run. Alternatively, the previously-generated graphics are shown in the static rendering available [here](https://nbviewer.jupyter.org/github/fomightez/synchro-binder/blob/master/index.ipynb).


License for SynChro software
----------------------------

[The article](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0092621) for SynChro states it is released under a BSD license.

This is `license.txt` within `CHROnicle/Programs/1SynChro` available after the preoaration step in the Quick start is run:

```
SynChro: a tool to reconstruct and visualize Synteny blocks along Chromosomes
Copyright (c) 2013, Guénola DRILLON, Alessandra CARBONE, Gilles FISCHER
                    UMR 7238 Génomique des Microorganismes
                    CNRS - Université Pierre et Marie Curie
All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice,
  this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

```

Related software
----------------

I have set up another repository that launches an active Jupyter session with alternative software for syntenic comparisons and visualizations:

- MCscan software (Python version) facilitates pairwise and multiple genome syntenic comparisons and visualizations. MCscan is an application within the JCVI module.  Go [here](https://github.com/fomightez/mcscan-binder) to be able to learn more about MCscan and launch it.
  I have converted the software's 'example wokflow' to a Jupyter notebook and added some additional exploration of the features of the software beyond that. Hopefully, having working versions of that software along with the  MCscan software available here lowers the technical barriers that would normally detour interested persons from comparing and contrasting options with each set of software. In fact, this hopefully makes it easy to supplement analyses with one with use of features from the other.


Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

`csh` and `gnuplot` were necessary so `apt.txt` was used. BLAST was indicated in `environment.yml`.

I borrrowed the 'warning' highlight/introductory text about notebooks at the top of the included notebook from Tim Sherratt's notebook [here](https://github.com/GLAM-Workbench/te-papa-api/blob/master/Exploring-the-Te-Papa-collection-API.ipynb).

Click this button below to begin using SynChro:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fomightez/SynChro-binder/master?filepath=index.ipynb)
