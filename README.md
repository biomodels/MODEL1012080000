# MODEL1012080000: Heitzler2012_GPCRsignalling

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1012080000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1012080000.git@20140916`

## Usage

Importing the model package.

`import MODEL1012080000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Competing G protein-coupled receptor kinases balance G protein and β-arrestin signaling**   
Heitzler D, Durand G, Gallay N, Rizk A, Ahn S, Kim J, Violin JD, Dupuy L,
Gauthier C, Piketty V, Crépieux P, Poupon A, Clément F, Fages F, Lefkowitz RJ,
Reiter E. _Mol Syst Biol._ 2012; 8: 590.
[22735336](http://www.ncbi.nlm.nih.gov/pubmed/22735336) ,  
**Abstract:**   
Seven-transmembrane receptors (7TMRs) are involved in nearly all aspects of
chemical communications and represent major drug targets. 7TMRs transmit their
signals not only via heterotrimeric G proteins but also through β-arrestins,
whose recruitment to the activated receptor is regulated by G protein-coupled
receptor kinases (GRKs). In this paper, we combined experimental approaches
with computational modeling to decipher the molecular mechanisms as well as
the hidden dynamics governing extracellular signal-regulated kinase (ERK)
activation by the angiotensin II type 1A receptor (AT(1A)R) in human embryonic
kidney (HEK)293 cells. We built an abstracted ordinary differential equations
(ODE)-based model that captured the available knowledge and experimental data.
We inferred the unknown parameters by simultaneously fitting experimental data
generated in both control and perturbed conditions. We demonstrate that, in
addition to its well-established function in the desensitization of G-protein
activation, GRK2 exerts a strong negative effect on β-arrestin-dependent
signaling through its competition with GRK5 and 6 for receptor
phosphorylation. Importantly, we experimentally confirmed the validity of this
novel GRK2-dependent mechanism in both primary vascular smooth muscle cells
naturally expressing the AT(1A)R, and HEK293 cells expressing other 7TMRs.


