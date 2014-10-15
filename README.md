# BIOMD0000000071: Bakker2001_Glycolysis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000071.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000071.git@20140916`


# Model Notes


.

.

.

** [SBML](http://www.sbml.org/) level 2 code generated for the JWS Online project by Jacky Snoep using [PySCeS](http://pysces.sourceforge.net/)   
Run this model online at
[http://jjj.biochem.sun.ac.za](http://jjj.biochem.sun.ac.za/)  
To cite JWS Online please refer to: Olivier, B.G. and Snoep, J.L. (2004) [Web-
based modelling using JWS
Online](http://bioinformatics.oupjournals.org/cgi/content/abstract/20/13/2143)
, Bioinformatics, 20:2143-2144 **

.

.

_Biomodels Curation:_ The paper refers to the model equations present in
Bakker et al's " Glycolysis in bloodstream from Trypanosoma brucei can be
understood in terms of the kinetics of glycolytic enzymes" (Pubmed ID:
9013556), also, the authors claim that some of the modifications in these
equations were made based on the experimental results from the paper
"Contribution of glucose transport in the control of glycolytic flux in
Trypanosoma brucei" (Pubmed ID: 10468568). The model reproduces the various
flux values in Fig 3 for 100% TPI activity. It also matches with the values
provided in Table 2 of the paper. The model was successfully tested with
Copasi and SBML ODE Solver.  
The volumes are set to the values containing 1 mg of total protein per
microlitre total cell volume. To change the protein concentration use _Vt_ ,
the total cell volume in micro litre per mg protein.  
To change the TPI activity use the global parameter _TPIact_ .

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


