# BIOMD0000000331: Larsen2004_CalciumSpiking_EnzymeBinding

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000331.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000331.git@20140916`


# Model Notes


This a model from the article:  
** On the encoding and decoding of calcium signals in hepatocytes **   
Ann Zahle Larsen, Lars Folke Olsen and Ursula Kummera _Biophysical
Chemistry_Volume 107, Issue 1, 1 January 2004, Pages 83-99
[14871603](http://www.ncbi.nlm.nih.gov/pubmed/14871603),  
**Abstract:**   
Many different agonists use calcium as a second messenger. Despite intensive
research in intracellular calcium signalling it is an unsolved riddle how the
different types of information represented by the different agonists, is
encoded using the universal carrier calcium. It is also still not clear how
the information encoded is decoded again into the intracellular specific
information at the site of enzymes and genes. After the discovery of calcium
oscillations, one likely mechanism is that information is encoded in the
frequency, amplitude and waveform of the oscillations. This hypothesis has
received some experimental support. However, the mechanism of decoding of
oscillatory signals is still not known. Here, we study a mechanistic model of
calcium oscillations, which is able to reproduce both spiking and bursting
calcium oscillations. We use the model to study the decoding of calcium
signals on the basis of co-operativity of calcium binding to various proteins.
We show that this co-operativity offers a simple way to decode different
calcium dynamics into different enzyme activities.

**Note:**

This model corresponds to the improved model eqn 1-7, as described by Larsen
et al., 2004 implemented to investigate how the cell can decode different
oscillations. This is done by introducing 2 more variables Enzyme and Product
in addition to the 5 variables G-alpha, PLC, Ca_cyt, Ca_ER and Ca_mit
receptor-operated model described in the first part of the paper. The
receptor-operated model is itself a modified version of the model described in
Kummer 2000 (PMID:[10968983](http://www.ncbi.nlm.nih.gov/pubmed/10968983))


