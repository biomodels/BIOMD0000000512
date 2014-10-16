# BIOMD0000000512: MODEL1402030000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000512.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000512.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000512 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Benson2014 - FAAH inhibitors for the treatment of osteoarthritic pain

Evaluation of fatty acid amide hydrolase (FAAH) as a target for osteoarthritic
pain in humans, using an integrated systems pharmacology model.

The SBML version of the model is obtained from the supplementary material of
the corresponding paper (see below).

This model is described in the article:

[A systems pharmacology perspective on the clinical development of Fatty Acid
amide hydrolase inhibitors for pain.](http://identifiers.org/pubmed/24429592)

Benson N, Metelkin E, Demin O, Li GL, Nichols D, van der Graaf PH.

CPT Pharmacometrics Syst Pharmacol. 2014 Jan 15;3:e91.

Abstract:

The level of the endocannabinoid anandamide is controlled by fatty acid amide
hydrolase (FAAH). In 2011, PF-04457845, an irreversible inhibitor of FAAH, was
progressed to phase II clinical trials for osteoarthritic pain. This article
discusses a prospective, integrated systems pharmacology model evaluation of
FAAH as a target for pain in humans, using physiologically based
pharmacokinetic and systems biology approaches. The model integrated
physiological compartments; endocannabinoid production, degradation, and
disposition data; PF-04457845 pharmacokinetics and pharmacodynamics, and
cannabinoid receptor CB1-binding kinetics. The modeling identified clear gaps
in our understanding and highlighted key risks going forward, in particular
relating to whether methods are in place to demonstrate target engagement and
pharmacological effect. The value of this modeling exercise will be discussed
in detail and in the context of the clinical phase II data, together with
recommendations to enable optimal future evaluation of FAAH inhibitors.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1402030000](http://identifiers.org/biomodels.db/MODEL1402030000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


