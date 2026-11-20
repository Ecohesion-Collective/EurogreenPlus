# Eurogreen+

Eurogreen+ is an ecological macroeconomic model for analysing socioeconomic and energy transitions, with an empirically grounded baseline for Italy. It is introduced in:

> Cano Ortiz, D., D'Alessandro, S., Heydenreich, T., & Morlin, G. S. (2027). Eurogreen+: An integrated modelling framework for analysing socioeconomic and energy transitions. *Ecological Economics, 253*, 109261. https://doi.org/10.1016/j.ecolecon.2026.109261

## Overview

Eurogreen+ is a substantially revised version of the Eurogreen framework. It combines post-Keynesian macroeconomics, stock-flow consistent accounting, system dynamics and an input–output production structure with endogenous cost-driven technological change. It integrates the economic and energy systems, accounts explicitly for supply constraints, and features 100 representative households differentiated by region and income quintile.

## Repository contents

- `EurogreenPlus.mdl`: the model, programmed in Vensim. To open it, use Vensim DSS (requires a licence).
- `EurogreenPlus.vpmx`: packaged version of the model. It can only be opened with the free Vensim Model Reader (not with other Vensim versions), and it allows simulating the model and changing parameters, but not editing the model structure.
- `data_sources/`: folder with the data source files (`.xlsx`) and calibration files (`.out`) that the model reads.
- `Instructions to run the model.pdf`: step-by-step instructions to run the baseline scenario.

## Getting started

Download the entire contents of this repository into a single folder, keeping the `data_sources` folder next to the model file, and follow the step-by-step instructions in `Instructions to run the model.pdf` to run the baseline scenario.

To open the model you need either:

- **Vensim DSS** (https://vensim.com/, requires a licence), for `EurogreenPlus.mdl`; or
- the free **Vensim Model Reader** (https://vensim.com/free-downloads/), for `EurogreenPlus.vpmx`. This file does not open with the "Model Reader (Version 10.4)" listed on the download page. Use the one without a version label, which is version 11.0.0.

Tested with Vensim DSS 9.4.2 and Vensim Model Reader 11.0.0.

## Version

This repository contains version **1.0** of the model, the one used to produce the results in the paper.

## How to cite

If you use this model, please cite the repository using the "Cite this repository" button (see `CITATION.cff`) and the paper above.

## Contact

For questions, bug reports or suggestions, please open an issue in this repository.

## Acknowledgements

D.C.O. acknowledges funding by the European Union in the framework ot the Horizon Europe Research and Innovation Programme under grant agreement No. 101094546 (WISER: Well-being in a Sustainable Economy Revisited). S.D. and T.H. acknowledge funding by the European Union in the framework of the Horizon Europe Research and Innovation Programme under grant agreement number 101137914 (MAPS: Models, Assessment, and Policies for Sustainability). G.S.M. acknowledges funding from the Project Network 4 Energy Sustainable Transition – NEST, funded under the National Recovery and Resilience Plan (NRRP), Italy, under the Mission 4 Component 2 Investment 1.3 - Call for tender No. 1561 of 11.10.2022 of Ministero dell’Università e della Ricerca (MUR); funded by the European Union – NextGenerationEU: Award Number: Project code PE0000021. All opinions and remaining errors are our own.
