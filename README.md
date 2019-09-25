# visionlab-EEG-workshop

These are the materials and resources for Vision Lab EEG workshop on Sep 25th, 2019.

## Workshop Outline
**Part 1: Lecture**
* EEG basics and glossary (Dan)
* EEG Decoding (Ruosi)

**Part 2: MNE Tutorial Demo**
* [ERP Tutorial](https://github.com/narrow-street/visionlab-EEG-workshop/blob/master/EEG-ERP-Tutorial.ipynb) (Aylin)
* [Decoding/MVPA Tutorial](https://github.com/narrow-street/visionlab-EEG-workshop/blob/master/EEG-Decoding-Tutorial.ipynb) (Ruosi)

***
## Install MNE

You can follow either the MNE official [installation guide](https://www.nmr.mgh.harvard.edu/mne/stable/install/mne_python.html) 
or the following steps.

**Install MNE-Python and its dependencies in a virtual environment**
```
curl --remote-name https://raw.githubusercontent.com/mne-tools/mne-python/master/environment.yml
conda env create --name mne python=3.6.8 -f environment.yml
```
**Test MNE-Python Installation**
```
conda activate mne
python -c 'import mne; mne.sys_info()'`
```

***
## Resources
### Decoding Toolboxes

#### Python
* MNE (for M/EEG): [website](https://www.nmr.mgh.harvard.edu/mne)
* PyMVPA (for both fMRI, and M/EEG): [website](http://www.pymvpa.org/)
#### MATLAB
* Amsterdam Decoding and Modeling Toolbox (ADAM): [github](https://github.com/fahrenfort/ADAM), 
[paper](https://www.frontiersin.org/articles/10.3389/fnins.2018.00368/full)
* Neural Decoding Toolbox: [website](http://www.readout.info/)
* CosMoMVPA: [website](http://www.cosmomvpa.org/)

### Tutorials & Workshops
* A collection of MNE workshops: [github](https://github.com/mne-tools/mne-workshops)
* A comprehensive Group analysis demo MNE: [github](https://mne.tools/mne-biomag-group-demo), 
    [website](https://mne.tools/mne-biomag-group-demo/index.html),
    [paper](https://www.frontiersin.org/articles/10.3389/fnins.2018.00530/full)
* Luck Lab ERP bootcamp: [website](https://erpinfo.org/the-erp-boot-camp/)

***
## Review Papers
* Carlson, T. A., Grootswagers, T., & Robinson, A. K. (2019). An introduction to time-resolved decoding analysis for M/EEG. arXiv preprint arXiv:1905.04820.
* Grootswagers, T., Wardle, S. G., & Carlson, T. A. (2017). Decoding dynamic brain patterns from evoked responses: A tutorial on multivariate pattern analysis applied to time series neuroimaging data. Journal of cognitive neuroscience, 29(4), 677-697.
* Guggenmos, M., Sterzer, P., & Cichy, R. M. (2018). Multivariate pattern analysis for MEG: A comparison of dissimilarity measures. NeuroImage, 173, 434-447.
