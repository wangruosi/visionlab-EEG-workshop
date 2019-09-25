# visionlab-EEG-workshop

These are the materials and resources for Vision Lab EEG workshop on Sep 25th, 2019.

## Workshop Outline
**Part 1: Lecture**
* EEG basics and glossary (Dan)
* EEG Decoding (Ruosi)

**Part 2: Tutorial Demo**
* [ERP Tutorial](https://github.com/narrow-street/visionlab-EEG-workshop/blob/master/EEG-ERP-Tutorial.ipynb) (Aylin)
* [Decoding/MVPA Tutorial](https://github.com/narrow-street/visionlab-EEG-workshop/blob/master/EEG-Decoding-Tutorial.ipynb) (Ruosi)

## Install MNE

**Install MNE-Python and its dependencies in a virtual environment**
```
curl --remote-name https://raw.githubusercontent.com/mne-tools/mne-python/master/environment.yml
conda env create --name mne python=3.6.8 -f environment.yml`
```
**Test MNE-Python Installation**
```
conda activate mne
python -c 'import mne; mne.sys_info()'`
```
