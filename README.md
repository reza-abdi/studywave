# StudyWave 🧠🌊 (team: wedidathink)

# NatHacks Hackathon Project

Group member names (6 members):
1. Syed Reza Ali Abdi
2. Logan Hindley
3. Omar Mohamed
4. William Baird
5. Kenneth Joseph 
6. Muhammad Talha 

## Inspiration

Staying focused while studying is hard—especially when distractions are constant and invisible. We wanted to explore whether real-time EEG data could be used to measure focus and cognitive engagement, and then turn that invisible signal into something tangible and useful.

That idea became StudyWave: a project that transforms brainwaves into meaningful feedback to help users understand and improve their concentration.

## What It Does
StudyWave uses EEG data from a Muse headset to analyze brain activity and estimate a user’s focus level while studying.

The system:
+ Streams live EEG data
+ Filters and processes signals
+ Extracts meaningful features
+ Identifies periods of steady focus
+ Visualizes results for interpretation and experimentation

The goal is not diagnosis, but awareness—helping users see when they are focused and when their attention drifts.

## How It Works
1. EEG Data Collection
  EEG signals are streamed from a Muse headset using BrainFlow-compatible tooling.
2. Signal Processing
    + Noise filtering
    + Segmentation into time windows
    + Identification of steady vs. fluctuating brainwave patterns
3. Analysis & Experimentation
   Jupyter notebooks are used to test models, analyze trends, and visualize EEG signals associated with focus.
4. Visualization
  Graphs and prototype UI concepts show how real-time feedback could be delivered to users.
  


## Tech Stack
+ Python
+ Jupyter Notebooks
+ BrainFlow
+ NumPy / Pandas
+ Matplotlib
+ Muse EEG Headset
+ CSV-based signal analysis

## Getting Started
### Prerequisites
+ Python 3.x
+ Jupyter Notebook
+ BrainFlow
+ Muse EEG headset (or sample CSV data provided)

### Installation
```bash
pip install brainflow numpy pandas matplotlib jupyter
```

### Running the Project
1. Launch Jupyter Notebook:
```bash
jupyter notebook
```
2. Open one of the notebooks in src/ or src2/
3. Run cells sequentially to:
    + Load EEG data
    + Process signals
    + Visualize focus-related patterns

## Sample Data
If you don’t have access to a Muse headset, you can still experiment using:
+ steady_segments.csv
+ eeg_data_test.csv

These files contain EEG samples used during development and testing.

## Challenges We Faced
+ Filtering noisy EEG data
+ Defining what “focus” means quantitatively
+ Working with real-time biosignals under hackathon time constraints
+ Interpreting EEG patterns responsibly

## Accomplishments We’re Proud Of
+ Successfully streaming and processing EEG data
+ Identifying steady-focus segments
+ Building a reproducible analysis pipeline
+ Creating a strong foundation for real-time neurofeedback

## What We Learned
+ EEG data is powerful but noisy
+ Signal processing matters as much as machine learning
+ Even simple metrics can provide meaningful insights
+ Rapid prototyping is essential in neurotech

## What’s Next
+ Real-time focus scoring
+ Improved signal classification models
+ A fully interactive frontend
+ Personalized baselines per user
+ Integration with study tools (Pomodoro timers, productivity apps)

## Devpost
👉 Project Page:
https://devpost.com/software/wedidathink

## Team
Built with curiosity, caffeine, and brainwaves at NatHacks 🧠⚡

## Resources/Software
MUSE USAGE VIDEO: https://www.youtube.com/watch?v=omn7y3TIsGc
MUSE SDK INSTALLER: https://drive.google.com/drive/folders/1ID35qK7zCvRXmQTFsbDgmPkVGhnPeCxa?usp=sharing
https://portal.neuralberta.tech/course/3/md/55
https://www.youtube.com/watch?v=Qdwyhi2ulZU   <--- Useful brainflow video.
