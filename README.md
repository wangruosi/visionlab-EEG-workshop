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
**Step 1**: Make sure Anaconda and Python (> 3.5) are installed
```
conda --version && python --version
```

**Step 2**: Install MNE-Python and its dependencies in a virtual environment
```
curl --remote-name https://raw.githubusercontent.com/mne-tools/mne-python/master/environment.yml
conda env create --name mne python=3.6.8 -f environment.yml`
```
**Step 3**: Test MNE-Python Installation
```
conda activate mne
python -c 'import mne; mne.sys_info()'`
```
