The general concept of building a PBPK model has previously been described by e.g. Kuepfer et al. ([Kuepfer 2016](#5-References)). The relevant anthropometric (height, weight) and physiological information (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-References)). This information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

Variability of plasma proteins and CYP enzymes are integrated into PK-Sim® and described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-References)) or otherwise referenced for the specific process.

First, a base mean model was built using clinical data including single and multiple dose studies with oral applications of efavirenz (Sustiva) to find an appropriate structure to describe the pharmacokinetics in plasma. The mean PBPK model was developed using a typical European individual adjusted to the demography of the respective study population. The relative tissue-specific expressions of enzymes predominantly being involved in the metabolism of efavirenz were derived from RT-PCR data from [Nishimura 2003](#5-References) and are implemented in the model as described previously ([Meyer 2012](#5-References)).

Unknown parameters (see below) were identified using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility.

CYP3A4 plays only a minor role in efavirenz metabolism, and, therefore, auto-induction of CYP3A4 plays a minor role for efavirenz pharmacokinetics. Hence, to parameterize CYP3A4 induction, midazolam was used as victim substance and Emax and EC50 were identified by adjusted by . 

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#22-Data).

Details about the structural model and its parameters can be found in [Section 2.3](#23-Model-Parameters-and-Assumptions).

