## Morris Lecar Model Neuron
[![Continuous build using OMV](https://github.com/OpenSourceBrain/MorrisLecarModel/actions/workflows/omv-ci.yml/badge.svg)](https://github.com/OpenSourceBrain/MorrisLecarModel/actions/workflows/omv-ci.yml)

GitHub repository for an OSB project containing the Morris Lecar model.

This attempts to reproduce the model as defined [here](http://en.wikipedia.org/wiki/Morris%E2%80%93Lecar_model) (called `<morrisLecarWCell>` here). Note: the [Scholarpedia formulation of the model](http://www.scholarpedia.org/article/Morris-Lecar) (`<morrisLecarSCell>`) is slightly different. 

The model ComponentType definition(s) will be moved to the core set of NeuroML2 definitions when stable!

#### Installation

To get a local copy of this project [install git](https://help.github.com/articles/set-up-git) and type:

    git clone https://github.com/OpenSourceBrain/MorrisLecarModel.git
    cd MorrisLecarModel/NeuroML2

#### Test the project

Install jNeuroML 2, see [here](https://github.com/NeuroML/jNeuroML). Remember to set the **JNML\_HOME** environment variable.

Run the [example cell](https://github.com/OpenSourceBrain/MorrisLecarModel/blob/master/NeuroML2/Run_MorrisLecarWCell.xml) with:

    jnml Run_MorrisLecarWCell.xml

You should get the trace below (\*note: this is not identical to Figure 4 in [Morris & Lecar 1981](http://jaguar.biologie.hu-berlin.de/downloads/Fachkurs/SS2010/Morris_Lecar_1981.*) 

The definition in LEMS, [MorrisLecarWCell.xml](https://github.com/OpenSourceBrain/MorrisLecarModel/blob/master/NeuroML2/MorrisLecarWCell.xml), currently uses the formalism outlined [here](http://en.wikipedia.org/wiki/Morris%E2%80%93Lecar_model)):

![](https://raw.githubusercontent.com/OpenSourceBrain/MorrisLecarModel/master/NeuroML2/images/ML.png)


