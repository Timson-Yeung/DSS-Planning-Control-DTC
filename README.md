# Decision Support for Planning and Control in Digital Twin Construction
This is a public repository for supplementary material for the pair of companion papers on Decision Support for Planning and Control in Digital Twin Construction submitted to Automation in Construction

## Material Description
:page_facing_up: Usability Test Questionnaire.docx - Questionnaire used to collect feedback from usability tests on the prototype system in paper I

:page_facing_up: Supplementary Material.pdf - Decision trees used during model design and validation data on Value-Adding Ratio for predictive simulation in paper II

:file_folder: Parametric Generation Sample - a simplified AnyLogic simulation model with codes to parametrically generate agent instances for a simulation run. Folder also contains a sample dataset.

### Parametric Generation Testing Guide

1) Download and install the free Personal Learning Edition of the AnyLogic software: <https://www.anylogic.com/downloads/> AnyLogic Documentation: <https://anylogic.help/>
2) Open the :paperclip: **parametric_generation.alp** model file via AnyLogic
3) The input datasets are already linked to the _Database_ component of the model. During every simulation run initiation, the model database will refresh itself based on the linked excel sheets.
4) In the _Main_ agent, you can find 4 functions represented by a blue circle with letter _F_. These functions are called at the beginning of each simulation run to parametrically instantiate the agents according to the model database.
5) In the _Main_ agent are also empty agent populations (e.g., _crews[]_) which the instantiated agents will be populated into.
