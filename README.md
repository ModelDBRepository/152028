This is the modeling package to accompany paper by:

Cengiz Gunay, Fred Sieling, Logesh Dharmar, Wei-Hsiang Lin, Verena  
Wolfram, Richard Marley, Richard A. Baines, and Astrid A. Prinz.  
Title: TBD; in preparation.

Download from:  
[http://www.biology.emory.edu/research/Prinz/Cengiz/Gunay_etal_2014.zip](http://www.biology.emory.edu/research/Prinz/Cengiz/Gunay_etal_2014.zip)

Requirements:  
- XPPAUT 5.99 - [http://www.math.pitt.edu/~bard/xpp/xpp.html](http://www.math.pitt.edu/~bard/xpp/xpp.html)  
- Neuron 7.1 - [http://www.neuron.yale.edu](http://www.neuron.yale.edu)  
- PANDORA 1.3b - [http://software.incf.org/software/pandora](http://software.incf.org/software/pandora)

Directories:  
- channels/  
  Results of channel fits and related figures (see all_channels.m).  
- xpp-models/  
  Isopotential and ball-and-stick models and their figures (see figure_models.m).  
- morphological/  
  Multicompartmental model in Neuron (see figures.m).  
- param-fitter/  
  Matlab code used for channel parameter fitting (add to Matlab path).

Workflow/history of project:  
- Channel data were fit with the Neurofit tool and then re-adjusted with param-fitter in Matlab.  
- XPP models were built with these channels and hand-tuned to fit observed f-I, v-I, and delay.  
- Neuron model used these channels and some properties of the ball-and-stick model.  
- Morphological reconstruction passive parameters were tuned to recorded capacitance responses.  
- Channel distribution hand tuned to mimick observed current responses.

Note:  
- Matlab files are scripts with sections that correspond to  
  figures. They are NOT meant to be run as a whole. Sections must be run  
  separately.

Please report problems/suggestions/comments to:  
Cengiz Gunay (cengique AT users.sf.net)  
2014/01/08

---

2025-07-09: Converted README to Markdown.