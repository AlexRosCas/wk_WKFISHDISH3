# ToR b case studies

This directory contains a collection of example datasets developed for ToR b of
WKFISHDISH3. Each dataset is designed to highlight one (or more) specific
methodological challenge(s) commonly encountered when developing, fitting,
evaluating, and interpreting SDMs for marine species.

The datasets are not intended to represent complete ecological studies. Instead,
they provide simplified examples that allow participants to explore alternative
modelling approaches and evaluate their strengths and limitations under
controlled conditions.


## Objectives

The case studies are designed to support discussions on:

* data processing and quality control,
* observation and response distributions,
* treatment of zero observations,
* spatial and temporal structure,
* survey design and missing data,
* life-stage and seasonal variation,
* uncertainty and model evaluation,
* extrapolation and prediction.

Participants are encouraged to compare multiple modelling approaches and
critically evaluate their assumptions, strengths, and weaknesses.


## Available case studies

| Folder | Title                   | Main methodological challenge |
|--------|-------------------------|-------------------------------|
| `...`  | Additional case studies | To be added                   |


## General workflow

Each case study contains:

* a dataset (`.rds`),
* a README file describing the challenge,
* figures illustrating key patterns,
* metadata describing variables and assumptions.

Participants may use any modelling framework of their choice, including
generalised additive models (GAMs), spatiotemporal models, machine-learning
approaches, or other SDM methods.


## Data sources

The datasets are primarily derived from fishery-independent surveys available
through the ICES Database of Trawl Surveys (DATRAS), with additional processing
and aggregation performed for workshop purposes. Original data ownership and
usage restrictions remain with the respective data providers.


## Citation

If these datasets are used outside the workshop, please cite the original survey
data sources, acknowledge the workshop dataset compilation and consider
contacting the case study creator(s).


## Contact

Alan Baudron [<alan.baudron@gov.scot>](mailto:Alan.Baudron@gov.scot)
Manuel Hidalgo [<jm.hidalgo@ieo.csic.es>](mailto:jm.hidalgo@ieo.csic.es)
Tobias Mildenberger [<tobm@dtu.dk>](mailto:tobm@dtu.dk)
