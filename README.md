#### iWP3, Genome-scale metabolic model of _Shewanella piezotolerans_ WP3

Files in this repository represent the GEM of _Shewanella piezotolerans_ WP3. A manuscript associated with this repository is currently under review at the ASM journal _mSystems_:

>Keith Dufault-Thompson, Huahua Jian, Ruixue Cheng, Jiefu Li, Fengping Wang, and Ying Zhang. Genome-Scale Model of Shewanella piezotolerans Simulates Mechanisms of Metabolic Diversity and Energy Conservation. _mSystems_, _in review_, 2017

##### List of files
* model.yaml:
  >YAML configuration file for PSAMM. Designates the biomass equation and file paths to the reaction database, compound database, model reactions (defines a list of reactions included in the model), and media definition (defines exchange reactions and constraints). The model contains no special constraints to internal reactions, and the internal reaction constrains will be assigned in [PSAMM](https://zhanglab.github.io/psamm/) based on reversibility of reactions.

* reactions.yaml:
  >YAML file that defines reactions in the model. This file includes the id, name, equation, gene associations, subsystem assignments, and category of each reaction.

* basal_constraints.yaml
  >YAML file that defines the exchange reactions and the basal constraints used for model simulations. Carbon sources and electron acceptors are restricted to [0,1000] in the basal constraints, so the model would require change of these constraints to provide at least one carbon source and one electron acceptor in order to perform growth simulations.

* compounds.tsv:
    >TSV file that defines compounds in the model. This file includes the id, name, formula, and charge of each compound.
