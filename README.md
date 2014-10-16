# BIOMD0000000245: lei2001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000245.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000245.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000245 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This the model from the article:  
**A biochemically structured model for Saccharomyces cerevisiae.**   
Lei F, Rotbøll M, Jørgensen SB. _J Biotechnol._ 2001 Jul 12;88(3):205-21.
PMID: [11434967](http://www.ncbi.nlm.nih.gov/pubmed/11434967) ,DOI: [10.1016/S
0168-1656(01)00269-3](http://dx.doi.org/10.1016/S0168-1656\(01\)00269-3)

**Abstract:**   
A biochemically structured model for the aerobic growth of Saccharomyces
cerevisiae on glucose and ethanol is presented. The model focuses on the
pyruvate and acetaldehyde branch points where overflow metabolism occurs when
the growth changes from oxidative to oxido-reductive. The model is designed to
describe the onset of aerobic alcoholic fermentation during steady-state as
well as under dynamical conditions, by triggering an increase in the
glycolytic flux using a key signalling component which is assumed to be
closely related to acetaldehyde. An investigation of the modelled process
dynamics in a continuous cultivation revealed multiple steady states in a
region of dilution rates around the transition between oxidative and oxido-
reductive growth. A bifurcation analysis using the two external variables, the
dilution rate, D, and the inlet concentration of glucose, S(f), as parameters,
showed that a fold bifurcation occurs close to the critical dilution rate
resulting in multiple steady-states. The region of dilution rates within which
multiple steady states may occur depends strongly on the substrate feed
concentration. Consequently a single steady state may prevail at low feed
concentrations, whereas multiple steady states may occur over a relatively
wide range of dilution rates at higher feed concentrations.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


