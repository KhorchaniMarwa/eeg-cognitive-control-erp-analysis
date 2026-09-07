# EEG Cognitive Control ERP Analysis

This project is a hands-on exploration of EEG data analysis using Python and MNE-Python.

The main objective is to understand the complete workflow of Event-Related Potential (ERP) analysis, starting from continuous EEG recordings and progressing toward the analysis of brain responses associated with experimental events.

## Objectives

- Load and explore raw EEG recordings
- Understand EEG channels and sampling frequency
- Identify experimental events
- Preprocess EEG signals
- Create epochs around specific events
- Compute Event-Related Potentials (ERPs)
- Visualize and compare ERP responses

## Technologies

- Python
- MNE-Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
eeg-cognitive-control-erp-analysis/
├── data/
├── notebooks/
│   └── 01_explore_raw_data.ipynb
├── src/
├── figures/
├── README.md
└── .gitignore
```

Event Exploration

Experimental events are encoded in the stimulus channel `STI 014`.
MNE detected 320 events in the recording.

Each event is represented by three values:

`[sample number, previous trigger value, event ID]`

The event ID identifies the type of experimental event.

